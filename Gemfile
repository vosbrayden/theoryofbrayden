source "https://rubygems.org"

# Jekyll core
gem "jekyll", "~> 4.4.1"

# Optional theme (commented out because you're using a custom one)
# gem "minima", "~> 2.5"

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-paginate"
  gem "jekyll-seo-tag"
end

# Extra libraries for Ruby 3.4 compatibility
gem "csv"
gem "logger"
gem "base64"

# Windows-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching files
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# JRuby-specific
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
