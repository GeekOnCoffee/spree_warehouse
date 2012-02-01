source 'http://rubygems.org'

gem 'devise' , '1.5.3'
gem 'rails' , '3.2.1'
gem 'spree', :git => 'git://github.com/spree/spree.git' 
gem 'sqlite3'

group :test do
  gem 'guard'
  gem 'guard-rspec', '~> 0.5.0'
  gem 'rspec-rails', '~> 2.8.0'
  gem 'factory_girl_rails', '~> 1.6.0'
  gem 'cucumber-rails'
  gem 'ffaker'
  gem 'shoulda-matchers', '~> 1.0.0'
  gem 'capybara'
  gem 'selenium-webdriver', '2.16.0'
  gem 'database_cleaner', '0.7.1'
  gem 'launchy'

  platform :ruby_18 do
    gem 'rcov'
  end
  platform :ruby_19 do
    gem 'simplecov'
  end

end

platform :ruby_18 do
  gem "ruby-debug"
end

platform :ruby_19 do
  gem "ruby-debug19"
end

gemspec
