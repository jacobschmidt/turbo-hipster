turbo-hipster
=============

# Running the site for devlopment (Windows)

Install VirtualBox and Vagrant. Then from git project foler:

vagrant up
vagrant ssh
cd /vagrant
jekyll serve -w

# Running the site for development (linux and mac)
Make sure ruby is installed. Then from the git project folder, do:

gem install jekyll
bundle install

then:

jekyll serve -w

# References
- Vagrant / Jekyll: https://coderwall.com/p/xrfadg
- Jekyll documentation: http://jekyllrb.com/
- Markdown Syntax: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet