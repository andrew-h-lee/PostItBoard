# Post It Board

## Objective

A Post Message Application built using Ruby On Rails.
The Functionality is similar to a forum as well as supporting Users.
Users are allow to create new messages and respond to messages.

## Accomplished
* Create Model & Controller for message & comment
* Add functionality to create new messages
* Add CRUD (create, Read, Update, Destory) functionality to messages
* Navigation created for the app in the layout file
* Authentication for User (through Devise)
* Create nested routes for comments
* Add functionality to comments such as form partial, create action & partial file
* Users can add timestamps
* Users allowed to create message or comment as well as edit or delete
* includes CSS styles & content layout
* test code with Rspec

## Prerequisites / Tools Used
* Ruby On Rails (v4.2.0+)
* Bootstrap (v3.3.0+)
* Sass
* HTML & CSS

## Add Gems to `Gemfile` Document
* `gem bootstrap-sass`
* `gem simple_form`
* `gem sass-rails`
* Add `gem rspec-rails` & `gem capybara` under heading `group :development, :test do`
* Run on terminal `bundle install` & `rails s` to load up server.

## Coming Soon / To-Do List
* Add Image / File Upload Feature
* Add file upload Gem
