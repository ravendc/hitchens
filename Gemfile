# frozen_string_literal: true

source "https://rubygems.org"
gemspec

# for demo site
gem "jekyll-paginate"


#Adicional
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
gem 'kramdown', versions['kramdown']
gem 'rake'

gem 'wdm', '~> 0.1.0'