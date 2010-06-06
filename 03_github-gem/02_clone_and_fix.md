!SLIDE bullets
# Clone and Fix #

* Get the repo
* Make changes
* Fork repo
* Push changes
* Notify others

!SLIDE commandline
# Find and clone #

    $ gh clone --search "hello world"
    Select a repository to clone:
    1.  drnic/oss-8steps-app    # "hello world" demo app
    ? 1
    Initialized empty Git repository in 
      /Users/drnic/gems/oss-8steps-app/.git/

    $ cd oss-8steps-app
    $ git config remote.origin.url
    git://github.com/drnic/oss-8steps-app.git
    
!SLIDE code small
# home/index.html.haml #

    @@@ ruby
    # Add yourself
    %li
      Dr Nic -
      %a{ :href => 'http://github.com/drnic' } github
      \-
      %a{ :href => 'http://twitter.com/drnic' } @drnic
      \-
      %a{ :href => 'http://drnicwilliams.com' } drnicwilliams.com

!SLIDE commandline
# Commit changes #

    $ git commit -a -m "Added YOU to contribs"
    
    $ git push origin master
    ERROR!!

!SLIDE commandline
# Fork and push #

    $ gh fork
    $ git config remote.origin.url
    git@github.com:YOU/oss-8steps-app.git
    
    $ git push origin master
    $ gh network web

!SLIDE full-page
# Network graph #

TODO - insert sample image

!SLIDE commandline
# Notify others #

    $ gh home
