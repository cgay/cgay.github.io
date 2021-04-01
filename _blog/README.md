To update the site:

* cd into this directory
* `bundle exec jekyll build`
* `cp -r _site/* ../`
* If you added a new blog category you may need to `git add` the directory.
* `git commit -am ...`
* `git push origin master`

It seems to update the site pretty quickly (a minute or two) even though GitHub
says it could be up to 20 minutes.
