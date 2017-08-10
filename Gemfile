source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'bcrypt',                  '3.1.11'
gem 'bootstrap-sass',          '3.3.6'
gem 'bootstrap-will_paginate', '1.0.0'
gem 'carrierwave',             '1.1.0'
gem 'coffee-rails',            '4.2.1'
gem 'faker',                   '1.7.3'
gem 'fog',                     '1.40.0'
gem 'haml', '~> 5.0', '>= 5.0.2'
gem 'jbuilder',                '2.4.1'
gem 'jquery-rails',            '4.1.1'
gem 'mini_magick',             '4.7.0'
gem 'puma',                    '3.4.0'
gem 'rails',                   '5.0.1'
gem 'sass-rails',              '5.0.6'
gem 'turbolinks',              '5.0.1'
gem 'uglifier',                '3.0.0'
gem 'will_paginate',           '3.1.5'

group :development, :test do
  gem 'byebug',  '9.0.0', platform: :mri
  gem 'sqlite3', '1.3.12'
end

group :development do
  gem 'haml-lint', require: false
  gem 'listen', '3.0.8'
  gem 'rubocop', require: false
  gem 'spring', '1.7.2'
  gem 'spring-watcher-listen', '2.0.0'
  gem 'web-console', '3.1.1'
end

group :test do
  gem 'guard',                    '2.13.0'
  gem 'guard-minitest',           '2.4.4'
  gem 'minitest-reporters',       '1.1.9'
  gem 'rails-controller-testing', '0.1.1'
end

group :production do
  gem 'pg', '0.18.4'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
