source 'https://rubygems.org'

gem 'rails', '3.2.3'
gem 'jquery-rails'
gem 'slim'
gem 'simple_form'
gem 'dynamic_form'
gem 'resque'
gem 'decent_exposure'
gem 'squeel'

group :production do
  gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platform => :ruby

  gem 'uglifier', '>= 1.0.3'
end

group :development, :test do
  gem 'rake'
  gem 'faker'
  gem 'sqlite3'
  gem 'guard-cucumber'
  gem 'guard-rspec'
  gem 'cucumber-rails', :require => false
  gem 'annotate', :git => 'git://github.com/ctran/annotate_models.git'
  gem 'rspec-rails'
  gem 'capybara'
  gem 'launchy'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'simplecov'
  gem 'redis-store', '~>1.0.0'
  gem 'rack-perftools_profiler', :require => 'rack/perftools_profiler'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
