source 'http://rubygems.org'

gem 'rails', '3.2.1'

# Asset template engines
group :assets do
  gem 'stylus'
  gem 'uglifier', '>= 1.0.3'
  gem 'yui-compressor'
end

gem 'haml-rails'
gem 'jquery-rails'
gem 'thin'
gem 'coffee-rails', '~> 3.2.1'

# Deploy with Heroku
gem 'heroku'

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
end

group :development do
  gem 'sqlite3'
end

group :production do
  gem 'pg'
  gem 'therubyracer'
end