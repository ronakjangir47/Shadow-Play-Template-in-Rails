source 'https://rubygems.org'

gem 'rails', '3.2.6'
gem 'bootstrap-sass'
group :production, :test do
	gem 'mysql2'
	gem 'rspec-rails', '2.10.0'
end


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

gem 'therubyracer'

group :test do
	gem 'capybara','1.1.2'
end

group :production do
	gem 'pg', '0.12.2'
end