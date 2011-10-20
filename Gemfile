source 'http://rubygems.org'

gem 'rails', '3.1.0'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'haml-rails'
end

gem 'haml' 

gem 'mongo_mapper'
gem 'bson_ext'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

group :development, :test do
  gem 'sqlite3'
  gem "rspec"
  gem "rspec-rails"
  # Pretty printed test output
  gem 'turn', :require => false
end

group :production do
  gem 'pg'
end
