source 'https://rubygems.org'

gem 'rails', '3.2.2'
gem 'bootstrap-sass', '2.0.0'
gem 'bcrypt-ruby', '3.0.1'  

group :development do
  gem 'sqlite3', '1.3.5'
  gem 'rspec-rails', '2.8.1'
  gem 'guard-rspec', '0.5.5'
  gem 'annotate', '~> 2.4.1.beta'  
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.4'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
end

gem 'jquery-rails', '2.0.0'

group :test do
  gem 'rspec-rails', '2.8.1'
  gem 'capybara', '1.1.2'
  gem 'guard-spork', '0.3.2'
  gem 'spork', '0.9.0'

	# Test gems on Windows
	group :test do
  	gem 'rspec-rails', '2.8.1'
	  gem 'capybara', '1.1.2'
		gem 'rb-fchange', '0.0.5'
		gem 'rb-notifu', '0.0.4'
		gem 'win32console', '1.3.0'
	end 
end

group :production do
  gem 'pg', '0.12.2'
end

