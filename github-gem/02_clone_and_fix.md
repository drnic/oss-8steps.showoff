!SLIDE bullets
# Clone and Fix #

* Get the repo
* Make changes
* Fork repo
* Push changes
* Notify others

!SLIDE commandline incremental
# Find and clone #

    $ gh clone --search "hello world"
    Select a repository to clone:
    1.  drnic/drnic-hello-world    # "hello world" demo app
    ? 1
    Initialized empty Git repository in 
      /Users/drnic/gems/drnic-hello-world/.git/

    $ cd drnic-hello-world
    $ git config remote.origin.url
    git://github.com/drnic/drnic-hello-world.git
    
!SLIDE code
# Change README.md #

    ## Contributors
    * Dr Nic
    * YOU

!SLIDE bullets
# Commit changes #

    $ git commit -a -m "Added YOU to contribs"
    
    $ git push origin master
    ERROR!!

!SLIDE commandline
# Fork and push #

    $ gh fork
    $ git config remote.origin.url
    git@github.com:YOU/drnic-hello-world.git
    
    $ git push origin master
    $ gh network web

!SLIDE full-page
# Network graph #

TODO - insert sample image

!SLIDE commandline
# Notify others #

    $ github pull-request drnic
    $ gh home
    