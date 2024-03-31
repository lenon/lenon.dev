+++
title = "Résumé/CV"
menu = "main"
+++

## Summary

I am a Senior Software Engineer with more than ten years of experience in developing web
applications and APIs. I have a strong background in Ruby, Python, and JavaScript. I can learn and
adapt to new concepts quickly, thanks to my multidisciplinary and open-minded approach. Throughout
my career, I have worked with companies and teams of various sizes, always playing an active role in
technical decisions and delivering high-quality software.

## Tech skills

Languages: Ruby, Python, JavaScript (Node.js), Go, SQL (PostgreSQL).\
Frameworks and libraries: Ruby on Rails, React, FastAPI, Pandas, RSpec, Capybara, pytest, Jest.\
Cloud infrastructure: AWS (EC2, ECS, RDS, Lambda, SQS, CloudFormation), Docker, Kubernetes (EKS).\
Methodologies and practices: Agile, Scrum, Kanban, CI/CD, DevOps, TDD/BDD.

## Experience

{{< experience company="Navisite"
               position="Software Engineer"
               date="Nov 2017 – Present"
               location="Remote" >}}

Navisite is a cloud services provider and an IT consulting company. I'm part of
the team responsible for the multi-cloud provisioning platform.

* Developed the snapshots/backup platform with support for AWS EC2, RDS, Oracle
  Compute, and Azure Compute instances in multiple cloud regions and time zones.
* Developed integrations with 3rd-party cloud APIs, such as AWS (EC2, RDS, among
  others), Oracle Cloud, and Azure. These integrations are used in provisioning,
  maintenance, and disaster recovery automation.
* Developed the customer panel and admin interfaces using Ruby on Rails,
  PostgreSQL, and Sidekiq in the back-end. JavaScript and React in the
  front-end.
* Developed a new REST API for the platform, following the JSON API
  specification.
* Developed a command-line interface (CLI) for the REST API using Go. Migrated
  part of the platform towards a serverless architecture using Python and AWS
  Lambda with Docker (work in progress).

The Ruby stack includes Ruby on Rails for web applications and APIs, Sidekiq and
AWS SQS for background jobs, RSpec, VCR, and Capybara for automated tests. The
front-end stack includes JavaScript, React and Jest for automated tests. Lambda
functions are written in Python, tested with Pytest, and deployed as Docker
images. We use GitHub flow in our development workflow, with code reviews and a
complete CI/CD pipeline.

{{< experience company="Acesso"
               position="Software Engineer"
               date="Mar 2017 – Nov 2017"
               location="São Paulo, SP, Brazil" >}}

Acesso was a fintech specialized in payment solutions. I was part of the team responsible for core
services.

* Developed a new embossing system for prepaid credit cards using a microservices architecture. It
  was written in Clojure and used RabbitMQ for message exchange.
* Developed integrations with third-party APIs and services to automatically issue credit card
  numbers, add customer details, order credit cards from the provider, and ensure their delivery to
  customers.
* Implemented a complete CI/CD pipeline using Docker for the microservices.
* Implemented mock APIs to simulate third-party integrations. These mocks were used to automate
  tests and improve code quality.

Skills: Clojure, PostgreSQL, Docker, RabbitMQ, Ruby, CI/CD, TDD, Agile.

{{< experience company="Locaweb"
               position="Software Engineer"
               date="Oct 2013 – Feb 2017"
               location="São Paulo, SP, Brazil" >}}

Locaweb offers a range of services, including web hosting, cloud computing, and SaaS applications,
among other enterprise solutions. I was part of the SaaS division, specifically assigned to the
Email Marketing team.

* Refactored a large Ruby on Rails application that handled millions of requests per day and was
  used by hundreds of customers. I worked on migrating the core database from MongoDB to PostgreSQL,
  which resulted in reduced infrastructure costs, resolved scalability issues, and simplified system
  administration.
* Developed a Ruby migration tool to reliably transfer customer data from the legacy MongoDB
  application to the new PostgreSQL-based application with minimal or no downtime.
* Designed and implemented a multitenant solution for Rails with database sharding to provide
  customers with a faster and more secure experience, allow the database to scale as needed, and
  simplify its maintenance.
* Developed new features for the application and the public REST API using Ruby, Ruby on Rails,
  Sidekiq, and PostgreSQL in the back-end, and JavaScript, HTML, and CSS in the front-end. RSpec and
  Capybara were utilized for testing.

I was also assigned to work with the SMTP team, responsible for the transactional email service.
Some of my contributions included:

* Developed new features in the Python back-end and in the customer-facing Ruby on Rails
  application.
* Created a new email tracker using Python.
* Implemented a new analyzer for bounced emails.
* Developed new anti-abuse and anti-spam algorithms in the back-end.

Skills: Ruby, Ruby on Rails, Python, PostgreSQL, MongoDB, CSS, HTML, JavaScript, REST, TDD, CI/CD,
Agile.

{{< experience company="Concrete Solutions"
        position="Software Developer"
        date="Jun 2011 – Sep 2013"
        location="São Paulo, SP, Brazil" >}}

Concrete Solutions was a tech consulting company that provided software development and cloud
consulting services. I was part of the team responsible for developing a payment gateway for the
Brazilian e-commerce market.

* Developed the customer-facing website, a public REST API, and a back-office application for
  administrative tasks. The tech stack included Ruby, Ruby on Rails, and MySQL in the back-end,
  along with JavaScript and jQuery in the front-end. RSpec was used for automated testing.
* Integrated with third-party APIs to process payments, reconcile transactions, and implement
  support for anti-fraud analysis.

After that project ended, I was assigned to work on-site at Locaweb, one of Concrete Solutions'
customers. Some of my responsibilities included:

* Maintaining and developing new features for Ruby on Rails applications, which included MySQL or
  PostgreSQL databases, utilizing Resque or Sidekiq for background processing. RSpec was used for
  automated tests.
* Recovering a legacy platform offered by Locaweb for freelancers and digital agencies to promote
  their services. I addressed bugs, security issues, upgraded dependencies, and added tests with
  RSpec. This effort facilitated the addition of new features to the platform.

Skills: Ruby, Ruby on Rails, JavaScript, CSS, HTML, MySQL, PostgreSQL, CI/CD, TDD, Agile, Scrum.

{{< experience company="Astrus Digital"
               position="Software Developer"
               date="Aug 2010 – Jun 2011"
               location="Erechim, RS, Brazil" >}}

Astrus Digital is a digital agency that offers web development, e-commerce, and digital marketing
services.

* Developed websites for Astrus customers using HTML, CSS, and JavaScript in the front-end, and PHP
  and MySQL in the back-end.
* Developed new features for in-house projects, such as the content management system (CMS) and the
  e-commerce platform, using PHP and MySQL.
* Built a new platform for local e-commerce using Ruby, Ruby on Rails, and MySQL.
* Developed a proof of concept based on WordPress to reduce costs and the effort required to
  maintain an in-house CMS.
* Implemented new integrations with third-party payment systems in the e-commerce platform.

Skills: Ruby, Ruby on Rails, MySQL, JavaScript, CSS, HTML, PHP, WordPress.

{{< experience company="diHITT"
               position="Programmer"
               date="Mar 2009 – Jan 2010"
               location="Remote" >}}

diHITT was a Brazilian social news website where users could submit links to articles, discuss them,
and vote on these submissions.

* Developed new features in the back-end using Ruby, Ruby on Rails, and MySQL.
* Developed new features in the front-end using HTML, CSS, and JavaScript.
* Refactored the back-end to address scalability issues, reduce infrastructure costs, and improve
  response times.
* Implemented new algorithms and enhancements for existing features, such as voting, messaging, and
  sharing tools.

Skills: Ruby, Ruby on Rails, MySQL, JavaScript, CSS, HTML.

## Education

### Bachelor's Degree in Computer Engineering

Anhembi Morumbi University (UAM). 2012 - 2017. São Paulo, SP, Brazil.
