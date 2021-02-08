# Using Github Pages on Windows
Install Jekyll
- follow Jekyll documentation for windows

Initialize webiste
- cd C:\Users\sshel\Documents\GitHub\ssharma1991.github.io
- bundle init
- bundle add jekyll
- bundle exec jekyll new .
- EDIT Gemfile (uncomment "github-pages")
- bundle install
- if errors ADD in Gemfile [gem 'nokogiri', '~> 1.11.0.rc2']

Test Website Offline
- bundle update
- bundle exec jekyll serve
- http://127.0.0.1:4000/


# Using this repo
Since this repo has custom css and layouts, no GEM files are required and you can directly use
- jekyll build
- jekyll serve --watch


# Hosting My Personal Website using GitHub Pages
I built this website with help of awesome guide by [Jonathan McGlone](http://jmcglone.com/guides/github-pages/) which uses [Jekyll](https://jekyllrb.com/docs/home/), a simple, blog-aware, static site generator.