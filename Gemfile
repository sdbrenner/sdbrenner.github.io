source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Use GitHub Pages
# gem "jekyll
gem "github-pages", group: :jekyll_plugins
# Theme
gem "jekyll-theme-basically-basic"
# To upgrade, run `bundle update github-pages`.

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jekyll-algolia"
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


# related to Ruby 3.0+?
gem "webrick", "~> 1.8"

# github identified potential vulerability: 
# "Active Support Possibly Discloses Locally Encrypted Files #2"
# https://github.com/sdbrenner/sdbrenner.github.io/security/dependabot/2
gem "activesupport", ">= 7.0.7.1"

