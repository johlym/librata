# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "bootsnap", require: false
gem "bootstrap", "< 6"
gem "brakeman"
gem "importmap-rails"
gem "jbuilder"
gem "jquery-rails", "~> 4.5"
gem "lograge"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "rails", "~> 7.0.4"
gem "redis", "~> 4.0"
gem "sidekiq"
gem "sprockets-rails"
gem "stimulus-rails"
gem "turbo-rails"
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  gem "bundler-audit"
  gem "debug", platforms: %i[mri mingw x64_mingw]
  gem "dotenv"
  gem "rubocop"
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
end

group :development do
  gem "rack-mini-profiler"
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "rspec"
  gem "rspec-rails"
  gem "selenium-webdriver"
  gem "webdrivers"
end
