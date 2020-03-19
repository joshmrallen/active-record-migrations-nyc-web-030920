require_relative './config/environment'
require 'sinatra/activerecord/rake'

desc 'some console thing'
task :console do
  require 'irb'
  ARGV.clear
  IRB.start
end

desc 'testing my rake file'
task :raketest do
  puts 'it\'s working'
end