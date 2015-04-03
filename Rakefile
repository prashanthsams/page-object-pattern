require 'rubygems'
require 'rake/testtask'
require 'rspec/core/rake_task'
# gem 'ci_reporter'
# require 'ci/reporter/rake/test_unit'

task :default => :spec

RSpec::Core::RakeTask.new do |t|
  t.pattern = "*spec.rb"
  t.verbose = false
end
