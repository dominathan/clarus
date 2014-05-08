source 'https://rubygems.org'

ruby '2.0.0'
gem 'rails', '4.0.2'
gem 'pg', '0.17.1'
gem 'devise', '3.2.4' #authentication management
gem 'figaro', '0.7.0' #manage environement variables
gem 'thin', '1.6.1'
gem 'jquery-rails'
gem 'less-rails'

#rails 4 deprecated use of :assets group in gemfile
gem 'sass-rails', '~> 4.0.2'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'twitter-bootstrap-rails'
gem 'therubyracer', '0.11.4'

group :production do
  gem 'rails_12factor', '0.0.2'
end

group :development, :test do
  gem 'factory_girl_rails', '4.3.0'
  gem 'rspec-rails', '2.14.1'
  gem 'database_cleaner', '1.2.0'
  gem 'fakeweb', '1.3.0'
  gem 'capybara', '2.0.2'
  gem 'capybara-webkit', '1.1.1'
end

group :development do
  gem 'pry'
  gem 'better_errors', '1.1.0' #better error messages for debug
  gem 'quiet_assets', '1.0.2' #shortens server log output
  gem 'letter_opener', '1.2.0' #outgoing emails on browser instead
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

