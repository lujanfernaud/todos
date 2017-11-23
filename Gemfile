source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.4.1'

gem 'rails',                   '~> 5.1.4'
gem 'sqlite3'
gem 'puma',                    '~> 3.7'
gem 'sass-rails',              '~> 5.0'
gem 'uglifier',                '>= 1.3.0'
gem 'coffee-rails',            '~> 4.2'
gem 'turbolinks',              '~> 5'
gem 'jbuilder',                '~> 2.5'

group :development, :test do
  gem 'rspec-rails',           '~> 3.7', '>= 3.7.2'
end

group :test do
  gem 'capybara',              '~> 2.16', '>= 2.16.1'
  gem 'database_cleaner',      '~> 1.6', '>= 1.6.2'
end

group :development do
  gem 'listen',                '>= 3.0.5', '< 3.2'
  gem 'pry',                   '~> 0.11.2'
  gem 'pry-byebug',            '~> 3.5'
  gem 'pry-rails',             '~> 0.3.6'
  gem 'rubocop-rails',         '~> 1.1'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console',           '>= 3.3.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
