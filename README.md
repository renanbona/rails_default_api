# README

##### Prerequisites

The setups steps expect following tools installed on the system.

- Ruby [3.0.0]
- Rails [6.1.3]
- Postgresql

##### 1. Check out the repository

```bash
git clone git@github.com:renanbona/rails_default_api.git
```

##### 2. Configure environment variables

Copy the sample .env file and edit the environment variables as required.

```bash
cp .env_sample .env
```

##### 3. Install the gems

```ruby
bundle install
```

##### 4. Create and setup the database

Run the following commands to create and setup the database.

```ruby
bundle exec rake db:setup
```

##### 5. Start the Rails server

You can start the rails server using the command given below.

```ruby
bundle exec rails s
```

And now you can visit the site with the URL http://localhost:3000

##### 5. Tests

You can start run the tests with

```ruby
bundle exec rspec
```
