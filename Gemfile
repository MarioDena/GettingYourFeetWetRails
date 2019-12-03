source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

gem 'rails',        '6.0.1'
gem 'puma',         '4.3.0'
gem 'sass-rails',   '6.0.0'
gem 'uglifier',     '3.2.0'
gem 'coffee-rails', '5.0.0'
gem 'jquery-rails', '4.3.5'
gem 'turbolinks',   '5.0.1'
gem 'jbuilder',     '2.7.0'
gem 'webpacker', '~> 4.0'
gem 'bootsnap', '>= 1.4.5', require: false

group :development, :test do
  gem 'sqlite3', '1.4.1'
  gem 'byebug',  '9.0.6', platform: :mri
end

group :development do
  gem 'web-console',           '3.5.1'
  gem 'listen',                '3.1.5'
  gem 'spring',                '2.1.0'
  gem 'spring-watcher-listen', '2.0.1'
end

group :production do
  gem 'pg'
end


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
