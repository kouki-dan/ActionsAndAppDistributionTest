source "https://rubygems.org"

gem "fastlane", :git => "https://github.com/fastlane/fastlane.git",
                :branch => "master"


plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
