source 'http://rubygems.org'

gem 'spree', '~> 2.1.0'
gem 'spree_auth_devise', :git => 'https://github.com/spree/spree_auth_devise.git', :branch => '2-1-stable'


group :test do
  gem 'webmock'
  gem 'guard-rspec', '~> 4.0.0'
  gem 'capybara'
  gem 'rspec-rails', '~> 2.14.0'
end

group :development, :test do
  gem 'zeus', require: false
  gem 'sqlite3'
  gem 'factory_girl'
  gem 'factory_girl_rails'
end

group :development do
  gem 'annotate', '>=2.6.0'
  unless ENV['RM_INFO']
    gem 'pry-debugger'
    gem 'pry-rails'
    gem 'pry-rescue'
    gem 'pry-stack_explorer'
  end
end

gemspec
