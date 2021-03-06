source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

  ruby '2.6.5'

# Core
  gem 'rails', '~> 5.2.4'
  gem 'bootsnap', '>= 1.1.0', require: false

# Middleware
  gem 'pg', '>= 0.18', '< 2.0'
  gem 'puma', '~> 3.11'

# Frontend
  gem 'sass-rails', '~> 5.0'
  gem 'uglifier', '>= 1.3.0'
  gem 'coffee-rails', '~> 4.2'
  gem 'turbolinks', '~> 5'
  gem 'jbuilder', '~> 2.5'
  gem 'webpacker'
  gem 'kaminari-bootstrap'

# Backend
  gem 'carrierwave'
  gem 'mini_magick'
  gem 'rails_admin'
  gem 'cancancan'
  gem 'ransack'
  gem 'kaminari'
  # gem 'seed-fu', '~> 2.3'
  # gem 'slim-rails'
  # gem 'html2slim'

# Authentication
  gem 'devise'


group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'better_errors'
  gem 'pry-rails'
  gem 'binding_of_caller'
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'guard-rspec'
  gem 'rspec-rails'
  gem 'launchy'
  gem 'capybara'
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'selenium-webdriver'
  gem 'database_cleaner'
  gem 'webdrivers'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'letter_opener_web'
end

group :test do
  gem 'chromedriver-helper'
  gem 'webdrivers'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
