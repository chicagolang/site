desc "Start local server"
task :server do
  sh "bundle exec jekyll server"
end

desc "Push to github pages / site"
task :publish do
  sh "git push origin master:gh-pages"
end

desc "Generate a new event post"
task :new do
  date = Time.now.strftime("%Y-%m-%d")
  filename = "./_posts/#{date}-title-goes-here.md"
  sh "cp ./sample.yml #{filename}"
end