Cloned from http://www.allanlab.org/aboutwebsite.html

To run: 

sudo apt install ruby

gem install jekyll

gem install bundler

bundler install

bundler exec jekyll serve

## For sslab docker
```
cd /home/sslab-admin/sslab-website
git pull origin gh-pages # Or other branch
docker-compose down
docker-compose up -d
```