source :rubygems

gem 'sinatra'
gem 'sinatra-jsonp', :require => 'sinatra/jsonp'
gem 'datamapper'

group :development do
  gem 'shotgun'
  gem 'sqlite3'
  gem 'dm-sqlite-adapter'
  gem 'heroku'
  gem 'heroku_san'
end

group :test do
  gem 'rspec', '=2.2.0'
  gem 'rack-test', '=0.5.6'
  gem 'webrat'
  gem 'simplecov', :require => false
end

group :production do
  gem 'dm-postgres-adapter'
end
