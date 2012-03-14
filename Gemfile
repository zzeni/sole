source 'https://rubygems.org'

gem 'rails', '3.2.2'
gem 'haml-rails'

group :production do
  gem 'pg', '0.12.2'
end

group :development do
  gem 'pry'
end

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
end

group :test do
  gem 'shoulda-matchers'
  gem 'spork'
  gem 'webrat'
  gem 'capybara'
  gem 'simplecov',        :require => false
end

group :tasks do
  gem 'rspec'
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'therubyracer'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
