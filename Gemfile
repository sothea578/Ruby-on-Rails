source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem "rails", "~> 5.1.1"
gem "sqlite3"
gem "puma", "~> 3.7"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"
gem "therubyracer", platforms: :ruby

gem "coffee-rails", "~> 4.2"
gem "jquery-rails" , "~> 4.3.1"
gem "turbolinks", "~> 5"
gem "jbuilder", "~> 2.5"
# gem "redis", "~> 3.0"
# gem "bcrypt", "~> 3.1.7"

# gem "capistrano-rails", group: :development

gem "execjs"


group :development, :test do
  gem "byebug","~> 9.0.0", platforms: [:mri, :mingw, :x64_mingw]
  gem "capybara", "~> 2.13"
  gem "selenium-webdriver"
  gem "sqlite3"
end

group :development do
  gem "web-console", ">= 3.3.0"
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring" , "~> 2.0.2"
  gem "spring-watcher-listen", "~> 2.0.0"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]


group :production do
  #gem "pg", "~> 0.21.0"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]