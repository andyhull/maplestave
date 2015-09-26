source 'https://rubygems.org'

gem 'bootstrap-sass', '~> 3.3.5'
gem 'sass-rails'
gem 'compass'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
