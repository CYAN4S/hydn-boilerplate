source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# Because, you know, Hydn is one of the Jekyll themes.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!


# Using GitHub Pages to build, and host blog.
gem "github-pages", group: :jekyll_plugins


# If you want to use the latest Jekyll features,
# remove the `gem "github-pages", group: :jekyll_plugins` above and uncomment two lines below.
# To upgrade, run `bundle update`.
# If you have any trouble with the upgrade, remove `Gemfile.lock` file, and try again.
# Notice that if you use two lines below, IT WON'T WORK AT GITHUB PAGES.

# gem "jekyll"
# gem "hydn"


# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed"
end


# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end


# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]


# Add webrick manually
gem "webrick", "~> 1.7"
