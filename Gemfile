source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails", "~> 7.0.2", ">= 7.0.2.3"
gem "puma"
gem "jbuilder"
gem "bcrypt"
gem "bootsnap", require: false
gem "image_processing"
gem "mini_magick"
gem "active_storage_validations"
gem "faker"
gem "will_paginate"
gem "bootstrap-sass"
gem "bootstrap-will_paginate"
gem "sass-rails"
gem "webpacker"
gem "turbolinks"

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "sqlite3", "~> 1.4"
end

group :development do
  gem "web-console"
  gem "listen"
  gem "rack-mini-profiler"
  gem "spring"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
  gem "rails-controller-testing"
  gem "minitest"
  gem 'minitest-reporters'
  gem "guard"
  gem "guard-minitest"
end

group :production do
  gem "pg"
end