source 'http://rubygems.org'

ruby '2.0.0'

gem 'rails', '4.0.1'
gem 'sass-rails', '~> 4.0.1'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.1'
gem 'jquery-rails'
gem 'jbuilder', '~> 1.2'
gem 'ejs'
gem "compass-rails", "~> 1.1.2"
gem "devise", "~> 3.2.0"
gem 'transitions', '0.1.9', :require => ["transitions", "active_record/transitions"]
gem 'i18n-js'
gem 'rails-i18n'
gem 'configuration'
gem 'rails-observers', '~> 0.1.2'
# gem 'protected_attributes'
gem 'jquery-ui-rails'

group :production do
  gem 'pg'
end

group :development, :test do
  gem 'pg'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'jasmine', '~> 1.3.2'
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'database_cleaner'
end

group :travis do
  gem 'pg'
end

if ENV['TRAVIS'] == 'true'
  group :test do
    gem 'pg'
  end
end
