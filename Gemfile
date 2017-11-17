source 'https://rubygems.org'
require 'rbconfig'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '5.1.4'
gem 'rubyzoho'
gem 'google_url_shortener', '~> 1.1'
gem "recaptcha", require: "recaptcha/rails"
gem 'pg'
gem 'rake'
gem 'sorcery'
gem 'cancancan', '~> 1.10'
gem 'email_validator'
gem 'simple_form'
gem 'active_attr'
gem 'valid_email', '~> 0.0.4'
gem 'city-state'
gem 'cacheable_flash'
gem 'rest-client'
gem 'awesome_print'
gem 'jquery-rails'
gem 'haml'
gem 'will_paginate'
gem "test-unit", "~> 3.0"
gem 'curb', '~> 0.9.3'
gem 'rubyzip'
gem 'enlace-fiscal', :git => 'https://github.com/betterm/enlace_fiscal'
gem 'numbers_and_words', :git => 'https://github.com/kslazarev/numbers_and_words'
gem 'pg_search'
gem 'coupons'
gem 'capistrano-rails'
gem 'capistrano-sidekiq', github: 'seuros/capistrano-sidekiq'
gem 'capistrano3-puma', github: "seuros/capistrano-puma"
gem 'slackistrano'

gem 'bootstrap-multiselect-rails'
# gem 'unicorn'
gem 'i18n-tasks'
gem 'i18n-js', :git => 'https://github.com/fnando/i18n-js'
gem 'airbrake'
gem 'localized_country_select'
gem 'dynamic_sitemaps'

gem 'i18n-globals'
gem 'faker'
gem 'rqrcode'
gem 'rqrcode_png'
gem 'ransack'
gem 'cocoon'
gem 'delocalize'
gem 'virtus'
gem 'business_time'
gem 'table_print'
gem 'credit_card_validator'
gem 'attr_encrypted', "~> 3.0.0"
gem "nested_form"
gem 'stripe', :git => 'https://github.com/stripe/stripe-ruby'
gem 'paypal-sdk-rest'
gem 'aws-sdk', '~> 2'
gem "fog", "~> 1.0"
gem 'conekta', git: 'https://github.com/betterm/conekta-ruby'
gem 'barby'
gem 'js-routes'
gem 'momentjs-rails'
gem 'bootstrap3-datetimepicker-rails'
gem 'coderay', '~> 1.1', '>= 1.1.1'
gem 'exception_notification'
gem 'responders', '~> 2.3'
gem 'autoprefixer-rails'

# gem 'active_shipping', path: '../active-shipping'

# gem 'active_shipping', git: "git@bitbucket.org:enviaya/active-shipping.git", branch: 'master'
gem 'rabl'
gem 'savon'
gem 'geoip'
gem 'carrierwave'
gem 'sidekiq'
gem 'fuzzy-string-match'
gem 'puma'
gem 'spreadsheet'
gem 'factory_girl_rails'
gem 'whenever', :require => false
gem 'mail_interceptor'
gem 'andand'
gem 'google_currency' # in case of updating the version lookup workaround warning
gem 'working_hours'
gem 'countries'
gem 'stripe_event'
gem 'premailer-rails'
gem 'rails_email_preview'
gem 'tzinfo'
gem 'wkhtmltopdf-binary'
gem 'wicked_pdf'
gem 'gibbon', '3.0.1'
gem 'roo'
gem 'roo-xls'
gem 'iconv'
gem 'coffee-rails'
gem 'uglifier'
gem 'compass-rails'
gem 'sass-rails'
gem 'bootstrap-sass'
gem 'rack-cors'
gem 'rubyXL', '=3.1.0'
gem 'rack-timeout'
gem 'unf_ext'
gem 'dotenv-rails'
gem 'nokogiri', '>= 1.8.0'
gem 'rack-mini-profiler', require: false
gem 'dalli'
gem 'nilify_blanks'

group :development do
  gem 'pry'
  gem 'rails_best_practices', '~> 1.17'
  gem 'active_record_query_trace'
  gem 'haml-rails', '>= 0.3.4'
  gem 'foreman'
  gem 'launchy'
  gem 'thin'
  gem "slack-notifier"
  gem "bullet", '~> 5.5.1'
  gem "better_errors"
  gem "binding_of_caller"
  gem 'traceroute'
  gem 'brakeman', :require => false
  # gem 'rubocop', '~> 0.47.1', require: false
  gem "rubycritic", :require => false
end

group :test, :development do
  gem 'deadweight', :require => 'deadweight/hijack/rails'
  gem 'hipchat'
  gem 'its'
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'rspec-rails'
  gem 'capybara'
  gem 'capybara-email'
  gem 'database_cleaner'
  gem 'timecop'
  gem 'simplecov'
  gem 'shoulda-matchers'
  gem 'shoulda'
  gem 'cane'
  gem 'poltergeist'
  gem 'morecane'
  gem 'capybara-screenshot'
  gem 'selenium-webdriver', '2.53.2'
  gem 'rb-fsevent'
  gem 'growl'
  gem 'rspec_candy'
  gem 'byebug'
  gem 'letter_opener'
  gem "minitest", "~> 5.5"
end

# WebPay (CL)
gem "transbank-webpay", git: 'https://github.com/afromankenobi/transbank-webpay.git', branch: 'older_nokogiri_compatibility'
gem 'amazon-ses-mailer', '~> 0.0.4'