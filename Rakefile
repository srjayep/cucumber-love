require 'rake/clean'

CLEAN.include('tmp/**/*')

task :default => :clean do 
 sh "cucumber -t ~@pending ."
end
