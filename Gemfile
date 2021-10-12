# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

File.read('./.ruby-version')

gem 'bootsnap', '~> 1.4', '>= 1.4.1', require: false
gem "bootstrap", ">= 4.3.1"
gem 'coffee-rails', '~> 4.2', '>= 4.2.2'
gem 'devise', '~> 4.7'
gem 'figaro', '~> 1.1', '>= 1.1.1'
gem 'jbuilder', '~> 2.8'
gem 'jquery-rails', '~> 4.3', '>= 4.3.3'
gem 'pg', '~> 1.1', '>= 1.1.4'
gem 'puma', '~> 4.3'
gem 'rails', '~> 5.2', '>= 5.2.2'
gem 'sass-rails', '~> 5.0', '>= 5.0.7'
gem 'sidekiq', '~> 5.2', '>= 5.2.5'
gem 'turbolinks', '~> 5.2'
gem 'uglifier', '~> 4.1', '>= 4.1.20'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails', '~> 5.0', '>= 5.0.1'
  gem 'faker', '~> 1.9', '>= 1.9.3'
  gem 'pry-byebug', '~> 3.7'
  gem 'rspec-rails', '~> 3.8', '>= 3.8.2'
  gem 'rspec_junit_formatter', '~> 0.4.1'
  gem 'sandi_meter', '~> 1.2'
end

group :development do
  gem 'annotate', '~> 2.7', '>= 2.7.4'
  gem 'better_errors', '~> 2.5', '>= 2.5.1'
  gem 'guard-rspec', require: false
  gem 'husky', '~> 0.5.15'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'rubocop', '~> 0.65.0', require: false
  gem 'rubocop-rspec', '~> 1.32', require: false
  gem 'spring', '~> 2.0', '>= 2.0.2'
  gem 'spring-watcher-listen', '~> 2.0', '>= 2.0.1'
  gem 'web-console', '>= 3.7.0'
end

group :test do
  gem 'database_cleaner', '~> 1.7', '>= 1.6.2'
  gem 'nyan-cat-formatter', '~> 0.12.0'
  gem 'shoulda-matchers', '~> 4.0', '>= 4.0.1'
  gem 'simplecov', require: false
end
