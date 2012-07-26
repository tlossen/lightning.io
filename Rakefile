task :build do
  `jekyll`
end

task :deploy do
  `ssh www@lightning.io "cd domains/lightning.io && git pull"`
end