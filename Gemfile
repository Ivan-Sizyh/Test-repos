source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.4'

gem 'rails', '~> 7.0.8', '>= 7.0.8.1'

gem 'propshaft'

gem 'pg', '~> 1.1'

gem 'puma', '~> 5.0'

gem 'jsbundling-rails'

gem 'turbo-rails'

gem 'stimulus-rails'

gem 'cssbundling-rails'

gem 'jbuilder'

gem 'redis', '~> 4.0'

gem 'bootsnap', require: false

group :development, :test do

  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails'
  gem 'rspec-rails', '~> 3.8'

end

group :development do

  gem 'rubocop'
  gem 'rubocop-performance'
  gem 'web-console'

end

group :test do

  gem 'capybara'
  gem 'rails-controller-testing'
  gem 'selenium-webdriver'
  gem 'shoulda-matchers'

end
