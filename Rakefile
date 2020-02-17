#!/usr/bin/env rake
# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.
#require_relative 'config/application'
#Rails.application.load_tasks
#task default: %w[test]

#task :test do
#  ruby "test/test_helper.rb"
#end
require 'rake/testtask'

task default: %i(test)

Rake::TestTask.new do |t|
 t.pattern = 'test/*_helper.rb'
  t.warning = false
  t.verbose = true
end
#RAKEFILE
# run the tests
#rake
#require File.expand_path('../config/application', __FILE__)

#RailsStarter::Application.load_tasks
