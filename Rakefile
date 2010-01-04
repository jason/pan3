begin
  require 'nanoc3/tasks'
  require 'vlad'
  require 'rubygems'
  Vlad.load :scm => :git
rescue LoadError => e
    puts "unable to load Vlad #{e}"
end

Dir['tasks/**/*.rake'].sort.each { |rakefile| load rakefile }