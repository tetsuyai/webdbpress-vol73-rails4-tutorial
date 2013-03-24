source 'https://rubygems.org'

gem 'rails', '4.0.0.beta1'
gem 'sqlite3'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.0.1'

group :assets do
  gem 'sass-rails', '~> 4.0.0.beta1'
  gem 'coffee-rails', '~> 4.0.0.beta1'
  gem 'uglifier', '>= 1.0.3'
end

group :production, :staging do
  gem 'unicorn'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'debugger'
end

gem 'capistrano', group: :development
