task :default => [:view]

task :view => [:compile] do
  sh "open index.html"
end

task :compile do
  sh "haml index.haml >index.html"
end
