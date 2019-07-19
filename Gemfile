source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

gem 'rails'

gem 'puma'
gem 'webpacker'
gem 'jbuilder'

gem 'bootsnap', require: false

gem 'redis'

gem 'barnes'

group :development, :test do
  gem 'byebug'
  gem 'pry-rails'
  gem 'dotenv-rails'
  gem 'sqlite3'
end

group :development do
  gem 'web-console'
  gem 'listen'

  gem "better_errors"
  gem "binding_of_caller"

  gem 'spring'
  gem 'spring-watcher-listen'
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'

  gem 'chromedriver-helper'
  gem 'rspec-rails'
end

group :production do
  gem 'pg'
end

gem 'devise'
gem 'devise-jwt'
gem 'fabrication'
gem 'faker'
