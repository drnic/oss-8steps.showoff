!SLIDE bullets
# Philosophy #

* Write failing tests

!SLIDE bullets
# Tests #

* Writing tests is hard
* Worth the effort
* Outside-in

!SLIDE bullets
# Process #

* 1. Run project tests after clone
* 2. Install dev dependencies
* 3. Notice/fix the broken ones
* 4. Write a failing test
* 5. Write the fix
* 6. Commit

!SLIDE commandline
# Process example #

    $ gem install thegem --development
    $ rake -T
    $ rake test OR rake spec OR rake cucumber OR rake
    ... fix issue ...
    $ rake
    $ git commit -a -m "Nasty bug heroically fixed"

!SLIDE commandline
# Cucumber for Rubygems? #

    $ gem install newgem
    $ cd /my/gem
    $ rubigen rubygems install_cucumber
    $ cat features/step_definitions/common_steps.rb
    $ rake features


