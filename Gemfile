source 'http://rubygems.org'
ruby '2.3.3'

gem 'rails', '5.0.1'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '>= 5.0.6'
  gem 'therubyracer'
  gem 'uglifier', '>= 1.0.3'

  # Upload assets to AWS S3
  gem 'asset_sync'
  gem 'fog-aws'
end

gem 'bootstrap-sass', '~> 3.3.6'
gem 'bootstrap-social-rails', '>= 4.12.0'
gem 'jquery-rails', '>= 4.2.2'

gem 'http_accept_language'

# Mongo
gem 'mongoid'

# Omniauth
gem 'omniauth', '>= 1.6.1'
gem 'omniauth-github', '>= 1.2.3'
gem 'omniauth-twitter', '>= 1.4.0'

# Puma
gem 'puma'

# New Relic
gem 'newrelic_rpm'

# Memcached
gem 'dalli'
gem 'memcachier'

# Pagination
gem 'kaminari', '~> 1.0', '>= 1.0.1'
gem 'kaminari-mongoid', '~> 1.0'

# Notify exceptions
gem 'exception_notification', '>= 4.2.1'

# Static pages
gem 'high_voltage'
gem 'rdiscount'

# Async tasks
gem 'sucker_punch', '~> 2.0'

gem 'octokit'
gem 'twitter'

group :production do
  gem 'rails_12factor'
end

group :test do
  gem 'coveralls', require: false
  gem 'minitest-reporters'
  gem 'mocha', require: false
  gem 'simplecov', require: false
end

group :development do
  gem 'better_errors', '>= 2.1.1'
  gem 'binding_of_caller'
end

group :development, :test do
  gem 'byebug'
  gem 'pry'
  gem 'rubocop', '~> 0.47.0', require: false
  gem 'test-unit', '~> 3.0'
end
