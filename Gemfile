source 'https://rubygems.org'
#ビデオのセクション2レクチャー5の最初の方に講師のgemfileが見える
git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end
gem 'therubyracer', platforms: :ruby

gem 'rails', '~> 5.1.1'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'

gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

gem 'jquery-rails'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'devise'
gem 'toastr-rails'
gem 'bcrypt-ruby', '~> 3.0.0'
gem 'omniauth-facebook'
gem "paperclip", "~> 5.0.0"
gem 'dropzonejs-rails'
gem "figaro", "~> 1.1.0"
gem 'aws-sdk', '~> 2.3'


group :production do
	
	gem 'pg'
	gem 'rails_12factor'
end

group :development, :test do
	gem 'sqlite3'
end


group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
