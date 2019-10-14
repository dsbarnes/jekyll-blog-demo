# This Gemfile is used when running Jekyll locally i.e. it is ignored by
# Github Pages. Specifies the source and the gems needed to be downloaded
# (with set versions).
#
source "https://rubygems.org"

# This will help ensure the proper Jekyll version is running.
# (Note that this is not necessary if you have installed jekyll at the user level,
# unless you do want a specific local version.)
gem "jekyll", "~> 3.8.5"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
# You can omit the version.
gem "minima", "~> 2.0"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins

# Put plugins here.
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
end


### Windows ###

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem.
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?
