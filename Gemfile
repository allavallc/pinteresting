source 'https://rubygems.org'
ruby '2.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.9'

#****
# took out the below and put into group to separate development from production
# Use sqlite3 as the database for Active Record
#gem 'sqlite3'
# ****

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin]
gem 'bootstrap-sass'

#devise gem for user adding and authenticating
gem 'devise', '~> 3.1.0.rq2'

#below shows that you only need to use the sqlite3 for developemnt and test
group :development, :test do
  gem 'sqlite3'
end

# below says to use posgress for production
group :production do
  gem 'pg'
  gem 'rails_12factor'  
end