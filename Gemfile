# frozen_string_literal: true

source "https://rubygems.org"
gemspec

gem "jekyll", "~> 3.6.0"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem "jekyll-paginate", "~> 1.1.0"
  gem "jekyll-twitter-plugin", "~> 2.0.0"
  gem "jekyll-seo-tag"
end

require 'rbconfig'
  if RbConfig::CONFIG['target_os'] =~ /darwin(1[0-3])/i
    gem 'rb-fsevent', '<= 0.9.4'
  end
