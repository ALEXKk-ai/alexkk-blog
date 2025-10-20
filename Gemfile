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

# Use GitHub Pages bundle for compatibility (includes safe Jekyll 3.9+ and whitelisted plugins)
gem "github-pages", group: :jekyll_plugins

# Your customs (whitelisted/safe for Pages)
gem "jekyll-seo-tag", "~> 2.8", group: :jekyll_plugins
gem "jekyll-sitemap", "~> 1.4", group: :jekyll_plugins

# Ruby 3.4+ Stdlib Fixes (no conflict)
gem "csv", "~> 3.3"
gem "base64", "~> 0.2"
gem "logger", "~> 1.5"

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

group :jekyll_plugins do
  # Plugins go here (already listed above)
end