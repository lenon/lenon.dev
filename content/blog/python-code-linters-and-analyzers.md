---
title: "Python code linters and analyzers"
date: 2022-06-05T15:00:00Z
tags: [python, code quality, linters]
---

Code linters are great for finding errors, bugs, and code smells before they
reach production. They help keep the code base readable, maintainable, and
consistent. Some linters are focused only on code style, while others can offer
more in-depth refactoring suggestions.

In this post, I made a small list to compare some of the available code linters
for Python because a lot has changed since the last time I checked them. I
included a brief description of the most relevant features of each one of them,
and at the end of this post, I share what I think makes sense for new Python
projects.

Let’s get started by remembering what PEP 8 is.

## PEP 8

[PEP 8] is a document that defines a style guide for writing Python code. It
contains rules about the use of tabs or spaces, how many of them to use, how to
indent code, what is the correct order of imports, among many other suggestions.

Style linters for Python usually follow PEP 8.

[PEP 8]: https://peps.python.org/pep-0008/

## Black

[Black] is an auto-formatter for Python, similar to [gofmt]. It follows PEP 8,
has minimal configuration options, and is very opinionated about how your code
should look.

Black only cares about style, so it is [safe to use][Black safety]. It checks
that the code before and after formatting is semantically equivalent by
comparing their ASTs.

One of the advantages of using auto-formatters like Black is that they help
reduce _bikeshedding_ in code reviews. Developers will have more time to focus
on what is important since there's no code style to discuss. You just have to
run Black and that's all.

[Black]: https://github.com/psf/black
[Black safety]: https://black.readthedocs.io/en/stable/the_black_code_style/current_style.html#ast-before-and-after-formatting
[gofmt]: https://pkg.go.dev/cmd/gofmt

## Pylint

[Pylint] is a static code analyzer for Python. It can check for errors, code
style, code smells, suggest refactorings, and even detect duplicated code. It
follows PEP 8 by default, but it is also highly configurable, so you can adapt
it to follow your own conventions.

In my experience, Pylint is a powerful and useful tool. I like that it warns
about [mutable default arguments][Python mutable default arguments], unused
variables and imports, and many other issues. Unfortunately, it is a bit slow
for large projects, so if you want to integrate it with your CI workflow, you
may need to disable some [messages][Pylint messages].

It also emits some false positives that you may need to look at and even disable
depending on the context.

[Pylint]: https://github.com/PyCQA/pylint
[Pylint messages]: https://pylint.pycqa.org/en/latest/user_guide/messages/index.html
[Python mutable default arguments]: https://github.com/satwikkansal/wtfpython#-beware-of-default-mutable-arguments

## Pyflakes

[Pyflakes] is a simple tool that can detect code errors. It is a faster but
limited alternative to Pylint. It has no configuration, does not check for
style, and tries “very hard to never emit false positives.” Pyflakes is a good
alternative if Pylint is too slow for you.

[Pyflakes]: https://github.com/PyCQA/pyflakes

## pycodestyle

[pycodestyle] is another tool that can detect violations of PEP 8. It is fast, but
also very simple and limited in what it can detect. It's possible to configure
which messages to ignore.

[pycodestyle]: https://github.com/PyCQA/pycodestyle

## autopep8

[autopep8] can auto-format Python code to follow PEP 8. Under the hood, it uses
[pycodestyle].

[autopep8]: https://github.com/hhatto/autopep8

## Flake8

[Flake8] is a wrapper around [Pyflakes], [pycodestyle], and [McCabe complexity
checker]. It groups all those tools under a single command, and adds some
features, like the ability to skip files and ignore specific errors on a line.

[Flake8]: https://github.com/PyCQA/flake8
[McCabe complexity checker]: https://github.com/PyCQA/mccabe

## isort

[isort] is a tool focused on organizing imports. It is a highly configurable
auto-formatter and can sort imports alphabetically, into sections, and by type.
By default, it follows the order recommended by PEP 8. It has a profile that is
compatible with [Black].

[isort]: https://github.com/PyCQA/isort

## Bandit

[Bandit] is a code analyzer that is designed to find security issues. It can warn
about unsafe function calls, hardcoded paths, passwords, and insecure hashing
algorithms (like MD5, SHA1), among other things.

[Bandit]: https://github.com/PyCQA/bandit

## Vulture

[Vulture] is focused on finding unused Python code. It is useful to keep the
code base organized and reduce the burden of having to maintain code that is not
even used anymore.

In dynamic languages like Python, tools like Vulture will eventually incorrectly
flag or miss dead code. This does not make it less useful, but you'll need to
take a closer look to make sure the report makes sense or not.

[Vulture]: https://github.com/jendrikseipp/vulture

## Which one should I use?

Older projects are often more complicated to change and depend on various
aspects, like which Python is in use, if there's good test coverage (if any),
etc. It's hard to recommend anything that would work in all contexts.

On the other hand, if you are starting a new Python project or your project is
still small, I would recommend Black for style, isort for imports, and Pylint
for other refactoring suggestions. Bandit and Vulture are also good options to
use.
