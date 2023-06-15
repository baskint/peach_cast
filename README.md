# Peach Cast

This is a sample repo running a Rails 7 App with TailwindCSS and Stimulus 
App create script is:
`rails new peach_cast --css tailwind --database=mysql`

* Ruby version - 3.2.2
* Rails version - 7.0.5

* System dependencies
  on MacOS ARM chip install mysql using `brew install mysql`, followed by `gem install mysql2`.

* Configuration

* Database creation
  Create .env file
  Update the following keys
  ```
  DB_USER=<mysql_user>
  DB_PASSWORD=<mysql_pswd>
  ```

* Database initialization
  Run `rails db:create`

* Install TailWindCss using
`rails tailwindcss:instal`

* Test Suite TBD

* Services (job queues, cache servers, search engines, etc.) - TBD

* Deployment instructions - TBD

