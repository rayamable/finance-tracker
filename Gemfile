source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

gem 'rails', '~> 6.0.2', '>= 6.0.2.1'

gem 'puma', '~> 4.1'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 4.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'
gem 'devise'
gem 'devise-bootstrap-views', '~> 1.0'
gem 'iex-ruby-client'
gem "font-awesome-rails"
gem 'devise-bootstrapped', github: 'king601/devise-bootstrapped', branch: 'bootstrap4'


gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  
  gem 'sqlite3', '~> 1.4'
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2' 
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production do
  gem 'pg'
end

group :test do
  
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver' 
  gem 'webdrivers'
end


gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
