desc "run the server"
task :default do
  sh "ruby rps.rb"
end

desc "ejecuta con piedra"
task :rock do
  sh %q{curl -v 'http://localhost:8080?choice=rock'}
end

desc "ejecuta con papel"
task :paper do
  sh %q{curl -v 'http://localhost:8080?choice=paper'}
end

desc "ejecuta con tijeras"
task :scissors do
  sh %q{curl -v 'http://localhost:8080?choice=scissors'}
end
