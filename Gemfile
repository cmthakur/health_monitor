source 'https://rubygems.org'

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

# Specify your gem's dependencies in health_inspector.gemspec
gemspec

group :test, :development do
  gem 'pg'
  gem 'pry'
  gem 'redis'
end

group :test do
  gem 'simplecov', require: false
end
