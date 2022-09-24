# https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll
# Based on $ jekyll new --skip-bundle wibble # follow by move to here.

source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# Replace jekyll with github-pages, as in above docs URL.
# gem "jekyll", "~> 4.2.2"
gem "github-pages", "~> 227", group: :jekyll_plugins

# After running
#     $ bundle install
#     got end-of-life message from sass:

# Ruby Sass has reached end-of-life and should no longer be used.

# * If you use Sass as a command-line tool, we recommend using Dart Sass, the new
#   primary implementation: https://sass-lang.com/install

# * If you use Sass as a plug-in for a Ruby web framework, we recommend using the
#   sassc gem: https://github.com/sass/sassc-ruby#readme

# * For more details, please refer to the Sass blog:
#   https://sass-lang.com/blog/posts/7828841

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.5"
# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
