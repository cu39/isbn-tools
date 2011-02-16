require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|
    gemspec.name = "isbn-tools"
    gemspec.summary = "This library provides the ability to manipulate ISBN numbers"
    gemspec.description = "Validate, convert and hyphenation of ISBN numbers"
    gemspec.email = ""
    gemspec.homepage = "http://isbn-tools.rubyforge.org"
    gemspec.authors = ["Kosuke Tanabe"]
  end
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }
