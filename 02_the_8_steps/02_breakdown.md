!SLIDE bullets center
# 1. Get annoyed by a defect or missing feature #

* Personal Power - Tony Robbins
* Circle of Concern vs Circle of Influence - 7 Habits of Highly Effective People

![Ciricle Of Influence](images/ciricle-of-influence.gif)

!SLIDE full-page

![Serenity](images/serenity.png)

!SLIDE center
# 2. Find the source. #

![Searching Github In Chrome](images/searching-github-in-chrome.png)

!SLIDE center
# Managing search in Chrome #

![Chrome Search Tab Completion](images/chrome-search-tab-completion.png)


!SLIDE center
# 2a. Find the source. #

![Github Search Results](images/github-search-results.png)

!SLIDE center
# 2b. Anyone else fixed it? #

![Finding Patches](images/finding-patches.png)

!SLIDE center
# 2b. Anyone else fixed it? #

![Network Graph](images/network-graph.png)

!SLIDE center
# 3. Checkout the source #

![Cloning Repo](images/cloning-repo.png)

!SLIDE commandline
# 4. Snoop around #

    $ git clone http://github.com/schacon/showoff.git
    Initialized empty Git repository in /Users/drnic/Documents/ruby/gems/showoff/.git/
    ...
    Resolving deltas: 100% (587/587), done.
    
    $ cd showoff
    $ rake -T
    rake clean                      # Remove any temporary products.
    rake gem                        # Build gem into dist/
    rake gem:install                # Build and install as local gem
    rake gem:publish                # Push the gem to RubyGems.org
    rake package                    # Build gem and tarball into dist/
    $ ls
    LICENSE       README.txt  TODO.txt   example  public  showoff.gemspec
    README.rdoc   Rakefile    bin        lib      script  views
    
    # NO TESTS?!

!SLIDE commandline
# 4. Snoop around; Try #2 #

    $ git clone http://github.com/wycats/thor.git
    $ cd thor
    $ rake -T
    No Rakefile found (looking for: rakefile, Rakefile, rakefile.rb, Rakefile.rb)
    $ sudo gem install thor
    $ thor list
    default
    -------
    thor :build               # Build gem
    thor :install             # Install gem using sudo
    thor :spec                # Run specs
    ...
    $ thor :spec
    ....................................................
    498 examples, 0 failures



!SLIDE bullets
# 5. Make changes #  

    

!SLIDE bullets
# 6. Fork repository #  

!SLIDE bullets
# 7. Push changes #  

!SLIDE bullets
# 8. Announce changes #  

