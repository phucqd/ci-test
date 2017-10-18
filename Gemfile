source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.1'
gem 'mysql2', '~> 0.3.13'

gem 'jquery-rails'
gem 'turbolinks'
gem 'coffee-rails'
gem 'uglifier'
gem 'sass-rails'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'rspec-rails'
	gem 'pry'

  gem 'brakeman', require: false
  gem 'jshint'
  gem 'bundler-audit'
  gem 'rubocop', require: false
  gem 'rubocop-checkstyle_formatter', require: false
  gem 'scss_lint', require: false
  gem 'scss_lint_reporter_checkstyle', require: false
  gem 'eslint-rails', git: 'https://github.com/octoberstorm/eslint-rails'
  gem "rails_best_practices"
  gem 'reek'

  gem 'simplecov'
  gem 'simplecov-rcov'
  gem "simplecov-json"
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

# deploy
gem 'unicorn'
gem 'unicorn-worker-killer'
gem 'capistrano', '3.6.0'
gem 'capistrano-rails'
gem 'capistrano-rvm'
gem 'capistrano-sidekiq'
gem 'capistrano-bundler'
gem 'capistrano3-unicorn'
# gem 'capistrano-locally'
