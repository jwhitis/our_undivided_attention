source 'https://rubygems.org'
ruby '2.4.0'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'bootstrap-sass', '~> 3.4.1'
gem 'font-awesome-rails'
gem 'jquery-rails'
gem 'pg', '~> 0.18'
gem 'pry-rails', group: [:development, :test]
gem 'puma', '~> 3.0'
gem 'rails', '~> 5.0.1'
gem 'rails_12factor', group: :production
gem 'sass-rails', '~> 5.0'
gem 'sm_app_config'
gem 'turbolinks', '~> 5'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'uglifier', '>= 1.3.0'

group :development do
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end