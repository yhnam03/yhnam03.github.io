source "https://rubygems.org"

# Site-mode Gemfile: explicit Jekyll + theme for local builds and CI
gem "jekyll", "~> 4.4"
gem "jekyll-theme-simplex"

# Required for built-in WEBrick server on recent Ruby
gem "webrick", "~> 1.7"

# Windows file watcher (optional, improves dev experience on Windows)
gem "wdm", ">= 0.1.0", require: false if Gem.win_platform?

# Ensure stdlib gems required by some libraries are available as gems
gem "bigdecimal"
gem "logger"
