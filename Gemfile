# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll-theme-chirpy", "~> 7.2", ">= 7.2.4"

gem "html-proofer", "~> 5.0", group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]

# The CSV library provides a complete interface to CSV files and data.
# It offers tools to enable you to read and write to and from Strings or IO objects, as needed.
gem "csv", "~> 3.3"

# logger was loaded from the standard library, but will no longer be part of the default gems starting from Ruby 3.5.0.
# You can add logger to your Gemfile or gemspec to silence this warning.
gem 'logger', '~> 1.6'

# base64 was loaded from the standard library, but is not part of the default gems starting from Ruby 3.4.0.
# You can add base64 to your Gemfile or gemspec to silence this warning.
gem 'base64', '~> 0.2.0'
