source "https://rubygems.org"

gem "jekyll", "~> 4.2.2"
gem "jekyll-theme-primer", "~> 0.6.0"
gem "webrick", "~> 1.7"

# Pin ffi for Ruby 2.6 compatibility
gem "ffi", "~> 1.15.5"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.15"
  gem "jekyll-seo-tag", "~> 2.8"
end

# Windows and JRuby
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
