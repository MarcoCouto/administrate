source "https://rubygems.org"
ruby "3.2.2" unless ENV["CI"]

gemspec

gem "administrate-field-image"
gem "faker"
gem "front_matter_parser"
gem "globalid"
gem "image_processing"
gem "kaminari-i18n"
gem "pg"
gem "pundit"
gem "redcarpet"
gem "sentry-rails", ">= 5.18.2"
gem "sentry-ruby"
gem "unicorn"

gem "cssbundling-rails", "~> 1.4", ">= 1.4.1"
gem "jsbundling-rails", "~> 1.3", ">= 1.3.1"
gem "sprockets-rails", "~> 3.5", ">= 3.5.0"

group :development, :test do
  gem "appraisal"
  gem "awesome_print"
  gem "byebug"
  gem "dotenv-rails", ">= 3.1.3"
  gem "factory_bot_rails", ">= 6.4.4"
  gem "i18n-tasks", "1.0.15"
  gem "pry"
  gem "standard"
  gem "yard"
end

group :test do
  gem "ammeter"
  gem "capybara"
  gem "database_cleaner"
  gem "formulaic"
  gem "launchy"
  gem "selenium-webdriver"
  gem "shoulda-matchers"
  gem "timecop"
  gem "webmock"
  gem "webrick"
  gem "xpath", "3.2.0"
end

group :staging, :production do
  gem "rack-timeout"
  gem "uglifier"
end
