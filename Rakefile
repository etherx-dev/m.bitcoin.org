task :build do
  sh "staticmatic build ."
end

task :copy do
  sh "rm -r /srv/http/test/"
  sh "cp -r site /srv/http/test/"
end

task :start do
  sh "staticmatic preview ."
end
