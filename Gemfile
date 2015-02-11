source 'https://rubygems.org'

<<<<<<< HEAD

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.8'
# Use sqlite3 as the database for Active Record
#gem 'sqlite3'
gem 'mysql2'
=======
gem 'rails', '4.1.8'
gem 'spree', '2.4.2'
gem 'spree_api', '2.4.2'
gem 'spree_frontend', '2.4.2'
gem 'spree_core', '2.4.2'
gem 'railties', '4.1.8'
gem 'json', '1.8.2'
gem 'jquery-rails', '3.1.2'
### OpenShift Online changes:

# Fix the conflict with the system 'rake':
gem 'rake', '~> 0.9.6'

# Support for databases and environment.
# Use 'sqlite3' for testing and development and mysql and postgresql
# for production.
#
# To speed up the 'git push' process you can exclude gems from bundle install:
# For example, if you use rails + mysql, you can:
#
# $ rhc env set BUNDLE_WITHOUT="development test postgresql"
#
group :development, :test do
#  gem 'sqlite3'
  gem 'minitest'
  gem 'thor'
end

# Add support for the MySQL
group :production, :mysql do
  gem 'mysql2'
end

group :production, :postgresql do
#  gem 'pg'
end

### / OpenShift changes

>>>>>>> 7dadb2888b541202861cc341e2799ec9d8abf67b
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
<<<<<<< HEAD
gem 'jquery-rails'
=======
#gem 'jquery-rails', '~> 3.1.1' 
>>>>>>> 7dadb2888b541202861cc341e2799ec9d8abf67b
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]


<<<<<<< HEAD
gem 'spree', '2.4.3'
gem 'spree_gateway', github: 'spree/spree_gateway', branch: '2-4-stable'
gem 'spree_auth_devise', github: 'spree/spree_auth_devise', branch: '2-4-stable'
=======

>>>>>>> 7dadb2888b541202861cc341e2799ec9d8abf67b
