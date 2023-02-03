# Jekyll Server in a Docker container


CD to the folder with your jekyll src files

Build the instance, this performs the "bundle install".
```shell
docker run --rm --volume="$PWD:/srv/jekyll" -it jekyll/jekyll:$JEKYLL_VERSION jekyll build
```

Perform a "bundle exec jekyll liveserve"
```shell
docker run --name newblog --volume="$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll:$JEKYLL_VERSION jekyll serve --watch --drafts
```
After updating the content restart the docker instance

```shell
docker restart newblog
```


