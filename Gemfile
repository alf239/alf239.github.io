source "https://rubygems.org"

gem "jekyll", "~> 3.9.3"

gem "minima", "~> 2.5"

group :jekyll_plugins do
  gem "jekyll-avatar", "~> 0.7.0"
  gem "jekyll-feed", "~> 0.15.1"
  gem "github-pages", "~> 228"
  gem "github-pages-health-check", "~> 1.17.9"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]


gem "webrick", "~> 1.8"
