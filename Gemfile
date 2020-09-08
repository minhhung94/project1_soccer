source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.0'

gem "active_storage_validations", "0.8.2"
gem "bcrypt"
gem "bootsnap", ">= 1.4.2", require: false
gem "bootstrap-sass", "~>3.4.1"
gem "bootstrap-will_paginate", "1.0.0"
gem "coffee-rails", "~> 4.2"
gem "config"
gem "faker", "2.1.2"
gem "figaro"
gem "image_processing", "1.9.3"
gem "jbuilder", "~> 2.7"
# Use jquery as the JavaScript library
gem "jquery-rails", "~> 4.3", ">= 4.3.1"
gem "mini_magick", "4.9.5"
gem "mysql2", ">= 0.4.4"
gem "puma", "~> 4.1"
gem "rails", "~> 6.0.3", ">= 6.0.3.2"
gem "rails-controller-testing"
gem "rails-i18n"
gem "sass-rails", ">= 6"
gem "turbolinks", "~> 5"
gem "uglifier", ">= 1.3.0"
gem "webpacker", "~> 4.0"
gem "will_paginate", "3.3.0"

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem "rails_best_practices"
  gem "rubocop", "~> 0.74.0", require: false
  gem "rubocop-checkstyle_formatter", require: false

  gem "rubocop-rails", "~> 2.3.2", require: false
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
