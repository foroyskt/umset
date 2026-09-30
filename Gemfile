source "https://rubygems.org"
gem "jekyll", "~> 4.3.1"
# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-relative-links", "~> 0.6.1"
  gem "jekyll-redirect-from", "~> 0.16.0"
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
# logger 1.6.0 added a Fiber-local level override (@level_override), which
# Jekyll 4.3.1 trips over in LogAdapter#adjust_verbosity -> writer.level:
#   logger.rb: undefined method `[]' for nil (NoMethodError)
# Modern Rubies bundle logger >= 1.6, so pin below it.
gem "logger", "~> 1.5.3"
gem "just-the-docs"