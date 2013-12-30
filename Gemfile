source 'https://rubygems.org'
ruby "1.9.3"

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'rails', '4.0.2'
gem 'jquery-rails', '3.0.4'
gem 'bootstrap-sass', '2.0.4'
gem 'bcrypt-ruby', '3.0.1'
gem 'protected_attributes'
gem 'rails-observers'
gem 'actionpack-page_caching'
gem 'actionpack-action_caching'
gem 'activerecord-deprecated_finders'

group :development, :test do
  gem 'sqlite3', '1.3.8'
  gem 'rspec-rails', '2.11.0'
  gem 'guard-rspec', '0.5.5'
  gem 'spork', '0.9.2'
  gem 'guard-spork', '0.3.2'  
  gem 'annotate', '2.5.0'
  gem 'rb-inotify', '~> 0.8.8', :require => false
end

group :test do
  gem 'capybara', '1.1.2'
  gem 'factory_girl_rails', '4.1.0'
  # Test gems on Macintosh OS X
  gem 'rb-fsevent', '0.9.1', :require => false
  gem 'growl', '1.0.3'
end 

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 4.0.1'
  gem 'coffee-rails', '~> 4.0.0'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.3.0'
end

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor'
end

# To use ActiveModel has_secure_password
#gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
