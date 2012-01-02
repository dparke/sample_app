source 'http://rubygems.org'

gem 'rails', '3.1.1'

group :development, :test do
  gem 'sqlite3'
end

group :development do
  gem 'rspec-rails', '2.6.1'
end

group :test do
  gem 'rspec-rails', '2.6.1'
  gem 'webrat', '0.7.1'
  gem 'ZenTest'
  gem 'autotest-rails-pure'
  gem 'autotest-growl'
  gem 'spork', '0.9.0.rc8'
end

group :production, :staging do
  gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.1.4'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'