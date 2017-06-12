ruby '2.2.7'
source 'https://rubygems.org'

gem 'rails', '~> 5.0.0'
gem 'pg'
gem 'rugged', '0.21.0'
gem 'unf'
gem 'turbolinks'
gem 'actionpack-page_caching', git: 'https://github.com/rails/actionpack-page_caching.git', branch: 'master'

gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2.1'

group :development do
  gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
  gem 'capistrano', '~> 3.4',         require: false
  gem 'capistrano-rails', '~> 1.1',   require: false
  gem 'capistrano-rvm', '0.1.1',     require: false
  gem 'capistrano3-puma', '~> 1.0',   require: false
end

group :test do
  gem 'delorean'
  gem 'rails-controller-testing'
end

group :production do
  gem 'puma'
end
