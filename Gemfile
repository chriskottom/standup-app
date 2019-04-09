source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.2'

gem 'rails', '~> 6.0.0.beta3'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0'
gem 'webpacker', '>= 4.0.0.rc.3'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

gem 'bootsnap', '>= 1.4.1', require: false

# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

gem 'aasm'

gem 'lodash-rails'
gem 'local_time'
gem 'redis', '~> 4.0'

gem 'devise'
gem 'devise_invitable'
gem 'rolify'
gem 'cancancan'

gem 'paper_trail'
gem 'bootstrap'
gem 'friendly_id'
gem 'slim-rails'

gem 'sidekiq'
gem 'sinatra', github: 'sinatra/sinatra', require: false
gem 'sidekiq-statistic'

gem 'gravatar_image_tag'
gem 'country_select'
gem 'kaminari'

gem 'money-rails'

gem 'ransack'

gem 'slack-notifier'

gem 'premailer-rails'
gem 'griddler'
gem 'griddler-mailgun'

gem 'rollbar'

group :development, :test do
  gem 'byebug', platforms: [:mri]
  gem 'factory_bot_rails'
  gem 'capybara', '>= 2.15'
end

group :development do
  gem 'letter_opener'
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
  gem 'simplecov', require: false
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'rack-cors', require: 'rack/cors'
