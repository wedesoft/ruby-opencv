# Rakefile
require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('opencv', '0.0.7') do |p|
  p.description    = "OpenCV wrapper for Ruby."
  p.url            = "http://github.com/adamb/ruby-opencv"
  p.author         = "Masakazu Yonekura"
  p.email          = "masakazu.yonekura@gmail.com"
  p.ignore_pattern = ["tmp/*", "script/*", "ext/*.o"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }
