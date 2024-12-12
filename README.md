# README

This is the repo for my ecommerce app using Ruby On Rails, Tailwind, Stripe for payments and Devise for authentication


* Ruby version
`3.3.6`

* Configuration
Add your env variables to the `config/credentials.yml.enc` file. You can do this by running `bin/rails credentials:edit`

* Database creation
Locally I used sqlite3 as our database. I used PostgreSQL in production.

* Database initialization
run `bin/rails db:migrate` to create the tables

* Deployment instructions
I deployed on Render, create a free account here render.com
