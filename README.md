# Peak-Tech-Server

* Commands used:
  - rails g model user first_name last_name email password_digest
  - rails db:create; rails db:migrate
  - rails g model organization name address overview:text employees:integer team_size:integer website twitter logo
  - rails g model techStack name  
  - rails g model tagging organization:references tech_stack:references
* Update Gemfile



This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
