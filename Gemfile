source "https://rubygems.org"

# Jekyll version chính
gem "jekyll", "~> 4.3.2"

# Theme mặc định
gem "minima", "~> 2.5"

# Nhóm các plugin Jekyll
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag", "~> 2.8"
  gem "jekyll-sitemap", "~> 1.4"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows performance booster
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock http_parser.rb gem
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Add webrick
gem "webrick", "~> 1.8"
