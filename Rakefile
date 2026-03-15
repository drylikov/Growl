
$:.unshift 'lib'
require 'growl'
require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new "growl", Growl::VERSION do |p|
  p.author = "Denis Rylikov"
  p.email = "denis.rylikov@protonmail.com"
  p.summary = "growlnotify bindings"
  p.url = "http://github.com/drylikov/growl"
  p.runtime_dependencies = []
end

Dir['tasks/**/*.rake'].sort.each { |f| load f }