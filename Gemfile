source "https://rubygems.org"

ruby File.read(".ruby-version").strip
gem 'add-to-org'
gem 'add-to-org', "~> 3.0"
gem 'rake'

require 'add-to-org'
run AddToOrg::App

group :development, :test do
  gem 'rspec'
  gem 'rack-test'
  gem 'webmock'
end
