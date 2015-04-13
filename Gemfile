source 'https://rubygems.org'
ruby '2.0.0'

# PostgreSQL driver

# Sinatra driver
gem 'sinatra'
gem 'sinatra-contrib'

gem 'activesupport', '~>4.1'
gem 'activerecord', '~>4.1'

gem 'rake'
gem 'iconv'
gem 'shotgun'

gem 'bcrypt'
gem 'yelp'


# group :test do
#   gem 'shoulda-matchers'
#   gem 'rack-test'
#   gem 'rspec'
#   gem 'capybara'
# end

# group :test, :development do
#   gem 'factory_girl'
#   gem 'faker'
# end

gem 'sqlite3', :group => [:development, :test]
group :production do
  gem 'thin'
  gem 'pg'
end