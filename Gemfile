source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.5"
# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!


# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
source "https://rubygems.org"

gem "jekyll", "~> 4.3.3"  # Latest stable as of 2025
gem "jekyll-seo-tag", "~> 2.8"  # Auto-adds meta, OG, Twitter cards, and Article schema
gem "jekyll-sitemap", "~> 1.4"  # Generates sitemap.xml for better crawling
gem "jekyll-feed", "~> 0.17"  # For RSS/Atom feeds

# Ruby 3.4+ Stdlib Fixes (TODO: Remove when Jekyll updates dependencies)
gem "csv"      # Required for data parsing (e.g., in plugins)
gem "base64"   # Required for encoding (used in Jekyll internals)
gem "logger"   # Silences deprecation warning

group :jekyll_plugins do
  # Plugins go here (already listed above)
end
source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
gem "webrick", "~> 1.8"  # Fixes serve issues if needed