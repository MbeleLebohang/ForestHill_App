source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails',                        '5.1.4'
gem 'bcrypt',                       '3.1.11'
gem 'faker',                        '1.7.3'
gem 'carrierwave',                  '1.1.0'
gem 'puma',                         '3.9.1'
gem 'sass-rails',                   '5.0.6'
gem 'uglifier',                     '3.2.0'

gem 'coffee-rails',                 '4.2.2'
gem 'turbolinks',                   '5.0.1'
gem 'jbuilder',                     '2.7.0'

group :development, :test do
  gem 'byebug',platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara',                   '~> 2.13'
  gem 'selenium-webdriver'
  gem 'sqlite3',                    '1.3.13'
end

group :development do
  gem 'web-console',                '3.5.1'
  gem 'listen',                     '3.0.8'
  gem 'spring',                     '2.0.2'
  gem 'spring-watcher-listen',      '2.0.1'
end

group :test do
  gem 'rails-controller-testing',   '1.0.2'
  gem 'minitest-reporters',         '1.1.14'
  gem 'guard',                      '2.14.1'
  gem 'guard-minitest',             '2.4.6'
end

group :production do
  gem 'pg',                         '0.20.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]