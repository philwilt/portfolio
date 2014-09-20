source 'https://rubygems.org'

# styles and structure for bourbon
gem 'bitters'
# sass mixins
gem 'bourbon'

# grid framework for bourbon
gem 'neat'
# Spring speeds up development by keeping your application running in the
# background. Read more: https://github.com/rails/spring
# patterns for bourbon
gem 'refills'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# Use jquery as the JavaScript library
gem 'jquery-rails'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.6'

#CI integration
gem 'travis'

# Turbolinks makes following links in your web application faster.
# Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
  # Use SCSS for stylesheets
  gem 'sass-rails', '~> 4.0.3'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

group :development do

  gem 'spring'
  gem 'sqlite3'
  gem 'rails_layout'
end

group :test do
  gem 'minitest-rails-capybara'
  # gem 'turn'
  # linting
  gem 'rubocop'
  gem 'minitest-rails'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
  gem 'thin'
end
