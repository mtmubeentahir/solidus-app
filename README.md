# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

if you have to start implementing the solidus on your local machine this link will give you an initial guide https://guides.solidus.io/developers/getting-started/first-time-installation.html

* Ruby version
  2.7.4

* Rails version
  6.1.4

* System dependencies
  - ruby
  - rails
  - active_storage
  - db installations

* Configuration
  - db adaptors setup

* Installation Process
  # installs migrations
  bin/rails railties:install:migrations

  # runs migrations
  bin/rails db:migrate

  # seeds your database
  bin/rails db:seed

  # loads sample data
  bin/rails spree_sample:load

* Error Handeling
  # if find error "unknown attribute 'service_name' for ActiveStorage::Blob "
  rails active_storage:update
  rails db:migrate