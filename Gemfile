ruby '>= 2.6.6'

source "https://rubygems.org"

gem "jekyll", "~> 3.9"

gem "execjs", "2.8.1" # https://github.com/rails/execjs/issues/99
gem "autoprefixer-rails"
gem "sprockets", "~> 4"
gem "kramdown-parser-gfm", "~> 1.1.0"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.15"
  gem 'jekyll-redirect-from'
  gem 'jekyll-paginate-v2', '~> 3.0'
  gem 'jekyll-sitemap'
  gem 'jekyll-seo-tag'
  gem 'jekyll-assets', git: "https://github.com/envygeeks/jekyll-assets"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?

gem "html-proofer", "~> 3.19"
