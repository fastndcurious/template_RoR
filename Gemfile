# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

File.read('./.ruby-version')

gem 'bootsnap', '>= 1.1.0', require: false
gem 'bootstrap', '~> 4.1.3'
gem 'coffee-rails', '~> 4.2'
gem 'devise', '~> 4.5.0'
gem 'figaro', '~> 1.1.1'
gem 'jbuilder', '~> 2.5'
gem 'jquery-rails'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'rails', '~> 5.2.1'
gem 'sass-rails', '~> 5.0'
gem 'sidekiq', '~> 5.2.2'
gem 'turbolinks', '~> 5'
gem 'uglifier', '>= 1.3.0'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails', '~> 4.0'
  gem 'faker', '~> 1.8', '>= 1.8.7'
  gem 'pry-byebug', '~> 3.6'
  gem 'rspec-rails', '~> 3.7', '>= 3.7.2'
  gem "rspec_junit_formatter", '~> 0.4', '>= 0.4.1'
  gem 'sandi_meter', '~> 1.2'
end

group :development do
  gem 'annotate', '~> 2.7', '>= 2.7.4'
  gem "better_errors"
  gem 'guard-rspec', require: false
  gem 'husky', '~> 0.5.15'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'rubocop', '~> 0.60.0', require: false
  gem 'rubocop-rspec', '~> 1.30', '>= 1.30.1', require: false
  gem 'spring', '~> 2.0', '>= 2.0.2'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

group :test do
  gem 'database_cleaner', '~> 1.6', '>= 1.6.2'
  gem 'shoulda-matchers', '~> 3.1', '>= 3.1.2'
  gem 'simplecov', require: false
end
