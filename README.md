# General Information
## Current Project Status:
  * basic rails app created
  * in the middle of writing README
  * working on schema design
    - can be found under vendor/notes
  * Nothing else is done or started yet.

## Summary of this project / Overview
  * The name of the project
    - my-budget
  * The names of the developers on the project
    - Richard Joo
      + Email: richardjoo@gmail.com
      + git: http://www.github.com/richardjoo
  * A brief description of the project
    - simple budgeting app.
    - I am using excel to do my budgeting simply because there is no suitable tools out there that fits to my needs, at least for free.  I use mint.com but their budgeting section is somewhat limited and less flexible.  If mint.com provides a good budgeting, then I would use mint.com site and be happy with it.  But since it is not, I decided to build this one and see how it goes.
  * An outline of the technologies in the project
    - Framework
      + Rails
      + Bootstrap 3
    - programming language
      + Ruby / Rails
      + HTML
      + Javascript
      + Coffeescript
      + Ajax
      + HAML
    - database
      + PostgreSQL

# Required Environment / Minimum Setup
----------------------------------------------
  Ruby version.
    ruby 2.1.1p76 (2014-02-24 revision 45161) [i686-linux]

  Rails version
    Rails 4.1.5

  Minimum setup required to run the app. This should be checked by `rake dev:setup`.


# Accessing the Site
----------------------------------------------

Is it running WEBrick, pow, unicorn?
Do you need to use custom subdomains or hosts?


# Configuration
----------------------------------------------

Who do I speak with to get the values for configuration files?
Who/where do I go to for dev/production database dumps?


# Walkthrough / Smoke Test
----------------------------------------------

Describe a manual smoke test process to ensure that the env is running as it should be.


# Getting Started
  * A detailed spin-up process. This should include:
    - Instructions on installing any software the application is dependent on:
      + wkhtmltopdf,
      + PostgreSQL,
      + XQuartz.
    - Instructions on running the app. For rails apps you’ll want to include the
      + rake db:create db:migrate db:seed process here,
      + as well as instructions on starting a server (e.g. are we using pow, or just the default `rails s`)
  * A list of credentials that can be used to log in with each user type in the system and ideally the URL that a developer can log in from.
  * Any information about subdomains in the app (e.g.: api.myapp.dev/)

  When writing instructions pretend you’re writing them for someone who knows next to nothing about developing in the framework/language your application uses.


# Testing
  * All you need to include in the “Testing” section is the commands to run any of the test suites you have (e.g.: RSpec, Jasmine, Cucumber, Spinach) and any setup you need to do before-hand (e.g.: rake db:test:prepare). This section will be small but vital.

# Staging and Production Environment
  * The staging and production environment sections (one section per environment) should provide any information a developer might need to know about these environments.

  * Which server is the application on? Is it on Amazon Sydney? A server in the office? A data-centre down the road?
  * How can a developer connect to the server? Do they need particular permissions? Who do they need to talk to to get those permissions?
  * Where on the server is the application located
  * What is the deploy process for this server
  * Are there any other services on the box related to the app a developer will need to know about? Any cron jobs? Some Resque workers?

  Staging Environment
  ----------------------------------------------

  Where is it?
  How do I access it?
  Who do I speak with to get access?


  Production Environment
  ----------------------------------------------

  Where is it?
  How do I access it?
  Who do I speak with to get access?
  Is there a CDN? How does it work?
  Is there a particular release process?


# Design
----------------------------------------------

Spot for designers to put any information they need.


# known Issues / Gotcha
----------------------------------------------



# Extended Resources
----------------------------------------------

link to extended resources


# Maintaining
  * Readme updated date
  * Worst case scenario, you don’t maintain a README. You’ll burn in developer hell, sorry.

  Follow this steps:
  * Plan feature
  * Write tests
  * Implement functionality
  * Update README if required
  * Get code reviewed and ensure all your tests pass
  * Merge your feature
  * What am I getting by writing a good README?
  * Update weekly