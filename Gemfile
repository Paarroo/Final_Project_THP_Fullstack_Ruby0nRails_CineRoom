source "https://rubygems.org"
ruby "3.4.5"

# Production and Development gems
gem "rails", "~> 8.0.2.1"
gem "pg", "~> 1.6"
gem "puma", "~> 7.0"
gem "solid_cache"
gem "solid_queue"
gem "solid_cable"
gem "propshaft"
gem "importmap-rails", "~> 2.2"
gem "turbo-rails", "~> 2.0"
gem "stimulus-rails", "~> 1.3"
gem "tailwindcss-rails"
gem "jbuilder", "~> 2.14"
gem "devise", "~> 4.9"
gem "cancancan", "~> 3.5"
gem 'activeadmin', '~> 3.2'
gem "stripe", "~> 15.5"
gem "stripe_event", "~> 2.7"
gem "money-rails", "~> 1.15"
gem "kaminari", "~> 1.2"
gem "chronic", "~> 0.10"
gem "friendly_id", "~> 5.5"
gem "noticed", "~> 2.6"
gem "turbo_power", "~> 0.7"
gem "view_component", "~> 4.0"
gem "image_processing", "~> 1.2"
gem "aws-sdk-s3", require: false
gem 'cloudinary', '~> 2.4'
gem 'activestorage-cloudinary-service'
gem "premailer-rails"
gem "nokogiri"
gem "geocoder", "~> 1.8"
gem "opencage-geocoder", "~> 3.2"
# gem "leaflet-rails" # Using CDN instead
gem "valid_email2", "~> 7.0"
gem "rqrcode", "~> 3.1"
gem "mini_magick", "~> 5.3"
gem "sidekiq", "~> 8.0"
gem "bootsnap", require: false
gem "kamal", require: false
gem "thruster", require: false
gem "tzinfo-data", platforms: %i[windows jruby]
gem "rspec-rails", "~> 8.0"
gem 'factory_bot_rails', '~> 6.5'
gem 'faker', '~> 3.2'
gem 'whenever', require: false

# Development and Test gems
group :development, :test do
  gem "debug", platforms: %i[mri windows], require: "debug/prelude"
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
  gem "dotenv-rails"
  gem "pry-rails"
  gem "pry-byebug"
  gem "table_print"
  gem "rails-erd"
  gem "bullet"
  gem "annotate"
end

group :development do
  gem "web-console"
  gem "letter_opener"
  gem "letter_opener_web"
  gem "localhost"
  gem "rubocop-rails"
  gem "rubocop-performance"
  gem "better_errors"
  gem "binding_of_caller"
  gem "listen"
  gem "spring"
  gem "spring-watcher-listen"
  gem "rerun"
  gem "guard"
  gem "guard-rails"
  gem "guard-livereload"
  gem "rack-livereload"
  gem "colorize"
  gem "tty-spinner"
  gem "tty-progressbar"
  gem "awesome_print"
  gem "hirb"
  gem "rails_panel"
  gem "meta_request"
  gem "rails_semantic_logger"
  gem "lograge"
  gem "seed_dump"
  gem 'rails-i18n'
  gem 'devise-i18n'
  gem 'http_accept_language'
  gem 'i18n-tasks'
end

group :test do
  gem 'shoulda-matchers', '~> 6.0'
  gem 'nyan-cat-formatter', '~> 0.12'
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
  gem "simplecov", require: false
  gem "database_cleaner-active_record"
  gem "webmock"
  gem "vcr"
end

# Production gems
group :production do
  gem "rails_12factor"
  gem "rack-timeout"
  gem "newrelic_rpm"
  gem "sentry-ruby"
  # Performance optimizations
  gem "rack-attack"  # Rate limiting and request throttling
end
