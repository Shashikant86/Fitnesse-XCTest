source "https://rubygems.org"

gem 'cocoapods'
gem 'fastlane'

plugins_path = File.join(File.dirname(__FILE__), '.', 'Pluginfile')
eval(File.read(plugins_path), binding) if File.exist?(plugins_path)

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval(File.read(plugins_path), binding) if File.exist?(plugins_path)