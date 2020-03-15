# krish7919.github.io
My website


### To build and test the site locally

docker build -t beautiful-jekyll "$PWD"
docker run -d -p 4000:4000 --name beautiful-jekyll -v "$PWD":/srv/jekyll beautiful-jekyll
docker stop beautiful-jekyll; docker rm beautiful-jekyll

