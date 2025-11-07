# Gemfile

source "https://rubygems.org"

ruby "3.1.4"                            # specify the Ruby version
gem "bundler", "~> 2.4.22"             # enforce bundler version

# If you're building a gem (plugin) and using a .gemspec, include gemspec.
gemspec

# Additional dependencies for your plugin
gem "fluentd", "~> 1.18"               # ensure compatibility with Fluentd 1.x
gem "fluent-plugin-lm-logs"            # your plugin
gem "executable-hooks", "~> 1.7"       # add this to satisfy bundler on packaging
