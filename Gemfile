source "https://rubygems.org"

# Jekyll
# gem "jekyll", "~> 3.9.5"

# Jekyll theme for new websites (jekyll new)
gem "minima"

# GitHub Pages
gem "github-pages", "~> 231", group: :jekyll_plugins

# Additional plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem "jekyll-remote-theme", "~> 0.4.3"
  gem "webrick", "~> 1.8"
end

# tzinfo-data with library since Windows and JRuby do not
# include zoneinfo files
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?

# gfm parser for kramdown v2
gem "kramdown-parser-gfm"

# http_parser.rb v0.6.0 since onewer versions of the gem
# do not have a Java counterpart for JRuby.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
