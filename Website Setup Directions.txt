USE GITHUB PAGES ON WINDOWS

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