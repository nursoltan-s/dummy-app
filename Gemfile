source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

gem 'rails', '~> 6.0.1'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 4.3'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 4.0'
gem 'jbuilder', '~> 2.7'
gem 'redis', '~> 4.0'
gem 'image_processing', '~> 1.2'
gem 'devise', '~> 4.7', '>= 4.7.1'

gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails', '~> 3.9'
  gem 'shoulda-matchers', '~> 4.1', '>= 4.1.2'
  gem 'capybara', '~> 3.29'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'better_errors', '~> 2.5', '>= 2.5.1'
  gem 'annotate', '~> 3.0', '>= 3.0.3'
  gem 'rubocop', '~> 0.76.0', require: false
  gem 'reek', '~> 5.5'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
