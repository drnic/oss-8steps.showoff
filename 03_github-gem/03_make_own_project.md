!SLIDE commandline
# New project #

    $ mkdir oss-8steps-app
    $ cd oss-8steps-app
    $ touch README.md
    $ git init
    $ git add .
    $ git commit -m "Initial commit"

!SLIDE commandline
# Push to GitHub #

    $ gh create-from-local
    $ git config remote.origin.url
    git@github.com:drnic/oss-8steps-app.git

    $ git push origin master

!SLIDE commandline bullets
# Becoming a committer #

* Owner grants you commit rights
* You update your `origin` url: `git://` to `git@`
* You can delete your fork
* No prizes for "Most Forks"

