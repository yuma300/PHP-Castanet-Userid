require 'rake/clean'

task :default => :test

desc 'Run tests'
task :test do
  sh 'vendor/bin/phpunit tests/*Test.php'
end

desc 'Generate documentation'
task :doc do
  sh 'phpdoc --directory src --target doc'
end
