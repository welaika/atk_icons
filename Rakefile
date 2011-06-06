# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "atk_icons"
  gem.homepage = "http://github.com/welaika/atk_icons"
  gem.license = "MIT"
  gem.summary = %Q{A way to use the awesome Agile Toolkit Icon Set within your Compass project.}
  gem.description = %Q{A way to use the awesome Agile Toolkit Icon Set within your Compass project.}
  gem.email = "stefano.verna@welaika.com"
  gem.authors = ["Stefano Verna"]
end
Jeweler::RubygemsDotOrgTasks.new
