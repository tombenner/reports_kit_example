source 'https://rubygems.org'
git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end
ruby '2.2.2'
gem 'rails', '~> 5.1.0'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'
gem 'jquery-rails'
group :development, :test do
  gem 'dotenv-rails'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13.0'
  gem 'selenium-webdriver'
end
group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'active_hash'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'faker'
gem 'groupdate'
gem 'haml-rails'
gem 'high_voltage'
gem 'pg'
gem 'redcarpet'
gem 'seed_migration'
gem 'timecop'

gem 'reports_kit', github: 'tombenner/reports_kit'

group :development do
  gem 'binding_of_caller'
  gem 'html2haml'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'rails_layout'
end
