# Sample App via [Ruby on Rails Tutorial](https://www.learnenough.com/ruby-on-rails-6th-edition) Book

This is a great book on Ruby on Rails which takes me through a journey of creating a full fledge REST application from 0 to deployment using Ruby on Rails.
The development works with TDD (Test Driven Development) and MVC (Model-View-Controller) in mind which are a great addition and introduction to any application development.
The book also helps us deploy the application via Heroku platform.

## What I learned by doing this project

- Test Driven Development
- REST API
- HTML
- CSS, Sass & Bootstrap
- Ruby
- Ruby on Rails
- Deployment to Production via Heroku
- Ajax

## Features of the App

- Account creation and validation
    - Includes security tests for validation and admin privileges
- Account activation using tokens via email
- Password reset using tokens via email
- Login/Logout & authorization
- Session persistence
- Account settings/details with the ability to modify email, name, avatar
- Session persistence via cookies
    - With the addition of remember me functionality
- Pagination
- Microposts CRUD
- Image upload & validation
- Following functionality
    - With following users and posts
- Status feed

## Main Technologies

- Ruby on Rails
- Git & GitHub
- Heroku setup & deployment
- SQLite3 in Test & Development Environments
- PostgreSQL in Production Environment
- Puma server All Environments
- Sass & Bootstrap
- Ajax

### Extra Ruby Gems

- [bcrypt](https://rubygems.org/gems/bcrypt)
    - for `has_secure_password` and easy hashing
- [webpacker](https://rubygems.org/gems/webpacker)
    - to use javascript modules in Rails
- [faker](https://rubygems.org/gems/faker)
    - to be able to generate users for a database for test purposes
- [will_paginate](https://rubygems.org/gems/will_paginate)
    - to allow for an easier pagination
- [byebug](https://rubygems.org/gems/byebug)
    - for debugging purposes
- [minitest](https://rubygems.org/gems/minitest)
    - to allow tests integration
- [guard](https://rubygems.org/gems/guard)
    - to automatically run test on file changes