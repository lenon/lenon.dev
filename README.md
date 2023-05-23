# lenon.dev

This repository contains the source code for my blog at https://lenon.dev. It is
powered by Hugo and GitHub pages.

## Cloning

Run the following commands:

```sh
git clone git@github.com:lenon/lenon.dev.git
git submodule init
git submodule update
```

## Updating

There's a workflow that runs whenever a commit is pushed to the main branch. The
workflow builds the site with Hugo and pushes changes to the `gh-pages` branch.
GitHub pages then publishes the site.
