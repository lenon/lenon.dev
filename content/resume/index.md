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

Navisite is a cloud services provider and an IT consulting company. I’m part of
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

Acesso is a fintech specialized in payment solutions. I was part of the team
responsible for core services. Some of our achievements:

* Developed a new embossing system for prepaid credit cards. It had a
  microservices architecture, was written in Clojure, and used RabbitMQ to
  exchange messages.
* Developed integrations with 3rd-party APIs and services to automatically issue
  credit card numbers, add customer details, order credit cards from the
  provider and get them delivered to the customer.

I implemented a complete CI/CD pipeline with Docker as the deployment
environment for the microservices.

{{< experience company="Locaweb"
               position="Software Engineer"
               date="Oct 2013 – Feb 2017"
               location="São Paulo, SP, Brazil" >}}

Locaweb offers services of web hosting, cloud computing, and SaaS applications,
among other enterprise solutions. I was part of the SaaS division assigned to
the Email Marketing team. Some of our significant achievements were as follows:

* Refactored a large Ruby on Rails application that served millions of requests
  per day and was used by hundreds of customers daily. We migrated the core
  database from MongoDB to PostgreSQL and achieved the goals of reducing
  infrastructure costs, solve scalability issues, and simplify system
  administration.
* Developed a migration tool in Ruby to migrate customers' data from the legacy
  MongoDB application to the new PostgreSQL-based application. We designed the
  tool in a way that minimal downtime was required.
* Developed a multitenant solution with database sharding for the same
  application to provide customers with a faster and more secure experience,
  allow the database to scale when required, and simplify its maintenance.
* Developed new features for the application and the REST API with Ruby, Ruby on
  Rails, Sidekiq, and PostgreSQL in the back-end, JavaScript (with jQuery),
  HTML, and CSS in the front-end, RSpec, and Capybara for testing.

I was also assigned to work with the SMTP team, responsible for the
transactional email service.

* Developed new features in the Python back-end and also in the customer-facing
  Ruby on Rails application.
* Developed a new email tracker in Python.
* Developed new anti-abuse and anti-spam tools in the back-end application.
* Implemented a new analyzer for bounced emails.

{{< experience company="Concrete Solutions"
        position="Software Developer"
        date="Jun 2011 – Sep 2013"
        location="São Paulo, SP, Brazil" >}}

Concrete is a tech consulting company. They offer software development and cloud
consulting services to businesses in multiple industries. I worked for them in
the team responsible for the following projects:

* Development of a payment gateway for the Brazilian e-commerce market, which
  had a customer-facing website and a REST API for developers to integrate their
  systems.
* Development of a back-office application for customer support and other
  administrative tasks Integration with 3rd-party APIs to process payments,
  conciliate transactions, and add support for anti-fraud analysis.
* Development of open-source Ruby gems to abstract and simplify the integration
  with SOAP-based APIs from 3rd-party service providers.

The tech stack included Ruby, Ruby on Rails, MySQL, and JavaScript with jQuery.
We used RSpec and Capybara for automated tests.

After that project ended, I was assigned to work on-site at Locaweb developing
and maintaining Ruby on Rails applications. These applications had MySQL,
MongoDB, or PostgreSQL databases, and Resque or Sidekiq for background jobs. We
used RSpec and Capybara to write automated tests.

I also worked on recovering a legacy platform used by freelancers and digital
agencies to list their services. I fixed bugs and security issues, upgraded
dependencies, and added tests using RSpec. This recovery made it possible to add
new features to the platform.

{{< experience company="Astrus Digital"
               position="Software Developer"
               date="Aug 2010 – Jun 2011"
               location="Erechim, RS, Brazil" >}}

Astrus is a digital agency that offers web development, e-commerce, and digital
marketing services. My responsibilities there as a software developer included
developing and maintaining customers' websites and internal systems.

* Developed websites for customers using HTML, CSS, and JavaScript with jQuery
  and plain JS in the front-end, and PHP, MySQL in the back-end.
* Developed new features for in-house projects, such as the content management
  system (CMS) and the e-commerce platform using PHP and MySQL.
* Developed a new platform for local e-commerce using Ruby, Ruby on Rails, and
  MySQL.
* Developed a proof of concept based on WordPress to reduce costs and the effort
  required to maintain an in-house CMS.
* Implemented new integrations with 3rd-party payment systems in the e-commerce
  platform.

{{< experience company="diHITT"
               position="Programmer"
               date="Mar 2009 – Jan 2010"
               location="Remote" >}}

diHITT was a social news website where users could submit links to articles,
discuss and vote on these submissions. I worked remotely for this company as a
programmer and was responsible for developing new features and maintaining both
the back-end and the front-end.

* Developed new features in the front-end with HTML, CSS, and JavaScript with
  Prototype, jQuery, and plain JS.
* Developed new features in the back-end using Ruby, Ruby on Rails, and MySQL.
* Refactored the back-end to solve scalability issues, reduce infrastructure
  costs and improve response times.
* Implemented improvements for existing features such as voting, messaging, and
  sharing tools.

## Education

### Bachelor's Degree in Computer Engineering

Anhembi Morumbi University. 2012 - 2017. São Paulo, SP, Brazil.
