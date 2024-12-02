# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"

gem "rails", "~> 7.0.5"

gem "sprockets-rails"

gem "sqlite3", "~> 1.4"

gem "puma", "~> 5.0"

gem "importmap-rails"

gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

gem "bootsnap", require: false

gem "responders"

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "rubocop", require: false
  gem "rubocop-rails", require: false
end

group :development do
  gem "erb_lint", require: false, git: "https://github.com/Shopify/erb-lint.git", branch: "main"
  gem "web-console"
end

group :test do
end

gem "shakapacker", "~> 6.6.0"

gem "react-rails", "~> 2.7.1"
