source 'https://rubygems.org'

gem 'rails', '3.2.6'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'
gem 'therubyracer'
gem 'execjs'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'

gem "rspec-rails", ">= 2.10.1", :group => [:development, :test]
group :test do
  gem "cucumber-rails", ">= 1.3.0", :group => :test, :require => false
  gem "capybara", ">= 1.1.2", :group => :test
  gem "factory_girl_rails", ">= 3.3.0", :group => [:development, :test]
  gem "email_spec", ">= 1.2.1", :group => :test
  gem "database_cleaner", ">= 0.7.2", :group => :test
end
gem "launchy", ">= 2.1.0", :group => :test
gem "devise", ">= 2.1.0"
