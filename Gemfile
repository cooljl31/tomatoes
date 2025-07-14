source 'http://rubygems.org'
ruby '2.3.3'

gem 'rails', '7.1.0'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '>= 6.0.0'
  gem 'therubyracer'
  gem 'uglifier', '>= 1.0.3'

  # Upload assets to AWS S3
  gem 'asset_sync', '>= 2.1.0'
  gem 'fog-aws', '>= 1.3.0'
end

gem 'bootstrap-sass', '~> 3.3.6'
gem 'bootstrap-social-rails'
gem 'jquery-rails', '>= 4.3.0'

gem 'http_accept_language'

# Mongo
gem 'mongoid', '>= 7.0.12'

# Omniauth
gem 'omniauth', '>= 2.1.0'
gem 'omniauth-github', '>= 2.0.0'
gem 'omniauth-twitter'

# Puma
gem 'puma'

# New Relic
gem 'newrelic_rpm'

# Memcached
gem 'dalli'
gem 'memcachier'

# Pagination
gem 'kaminari', '~> 1.1', '>= 1.1.0'
gem 'kaminari-mongoid', '~> 1.0', '>= 1.0.2'

# Notify exceptions
gem 'exception_notification', '>= 4.5.0'

# Static pages
gem 'high_voltage'
gem 'rdiscount'

# Async tasks
gem 'sucker_punch', '~> 2.0'

gem 'octokit', '>= 4.7.0'
gem 'twitter'

group :production do
  gem 'rails_12factor'
end

group :test do
  gem 'coveralls', '>= 0.8.20', require: false
  gem 'minitest-reporters'
  gem 'mocha', require: false
  gem 'simplecov', require: false
end

group :development do
  gem 'better_errors', '>= 2.2.0'
  gem 'binding_of_caller'
end

group :development, :test do
  gem 'byebug'
  gem 'pry'
  gem 'rubocop', '~> 0.47.0', require: false
  gem 'test-unit', '~> 3.0'
end
