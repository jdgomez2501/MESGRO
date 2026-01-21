source "https://rubygems.org"

# GitHub Pages bundle (includes correct Jekyll + compatible plugins)
gem "github-pages", "~> 232", group: :jekyll_plugins

# Extra Jekyll plugins (only if not already included)
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
  gem "jekyll-paginate"
end

# Windows and JRuby timezone support
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# File watcher for Windows
gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]

# JRuby HTTP parser compatibility
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
