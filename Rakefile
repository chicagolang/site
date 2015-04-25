task :server do
  sh "bundle exec jekyll server"
end

task :publish do
  sh "git push origin master:gh-pages"
end

task :new do
  date = Time.now.strftime("%Y-%m-%d")
  filename = "./_posts/#{date}-title-goes-here.md"
  sh "cp ./sample.yml #{filename}"
end