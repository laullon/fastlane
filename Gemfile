source "https://rubygems.org"

gem "xcode-install", ">= 2.0.10" # needed for running xcode-install related tests

gem "danger", ">= 4.2.1", "< 5.0.0"
gem "danger-junit", ">= 0.7.3", "< 1.0.0"

gem 'listen', '~> 3.0'

gemspec path: "."

plugins_path = File.join(File.expand_path("..", __FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path)
