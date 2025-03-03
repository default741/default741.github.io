source "https://rubygems.org"

gem "minima", "~> 2.5"
gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  gem 'jekyll-feed'
  gem 'jekyll-get-json'
  gem 'jekyll-toc'
  gem 'jekyll-link-attributes'
  gem 'fiddle'
  gem 'faraday-retry'
end

group :other_plugins do
  gem 'css_parser'
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
gem "webrick", "~> 1.9"
