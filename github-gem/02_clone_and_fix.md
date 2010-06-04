!SLIDE commandline
# Clone and Fix #

!SLIDE commandline
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
    
!SLIDE bullets
# Make a change #

* Add yourself to README.md

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
