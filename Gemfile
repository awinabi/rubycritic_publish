source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.13'

# Use postgresql as the database for Active Record
gem 'pg'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.2'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

group :test, :development do
  gem 'rspec-rails'
  gem 'rspec', '> 3.0.0'
  gem 'rspec-activemodel-mocks'
  gem 'pry'
  gem 'pry-nav'
  gem 'hirb'          # nice styling of console output
  gem 'foreman'       # starting development environment

  # documentation
  gem 'redcarpet'
  gem 'yard'
  gem 'yard-rest'
end

group :test do
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'capybara-screenshot'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'simplecov', require: false
  gem 'fuubar'
  gem 'vcr'        # replay API calls without hitting the network
  gem 'webmock'    # fake out VCR for requests
  gem 'timecop'    # manipulate time!
  gem 'zonebie'    # randomize timezone for each test run
  gem 'test-unit'
end

group :development do
  gem 'recipient_interceptor'
  gem 'rack-mini-profiler'
  gem 'bullet'
  gem 'bundler-audit', require: false
  gem 'brakeman', require: false
  gem 'rails_best_practices', require: false
  gem 'rubocop', require: false
  gem 'rubycritic', require: false
end
