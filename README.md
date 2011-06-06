Agile Toolkit Icon Set Compass Extension
==========================

A way to use the awesome [Agile Toolkit Icon Set](http://www.agiletech.ie/blog/128x16x16) within your project.

Installation
============

From the command line:

    sudo gem install atk_icons

Installing into an existing project:

    # edit the project configuration file and add:
    require 'atk_icons'

    #from the command line
    compass install atk_icons

    #import the extension into your scss/sass file
    @import "atk_icons"

Or create a new project:

    compass create <project_name> -r atk_icons --using atk_icons

    #import the extension into your scss/sass file
    @import "atk_icons"

Usage Example
=============

    # for a list of all the icons available, see http://www.agiletech.ie/blog/128x16x16

    span.delete
      / this will add an :after pseudo-selector with the selected icon
      @import atk-icon-after("basic-ex")

    span.delete span.icon
      / alternatively, you can add a classic sub-element, and set the icon to it
      @import atk-icon("basic-ex")


Contributing to atk_icons
=========================

* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it
* Fork the project
* Start a feature/bugfix branch
* Commit and push until you are happy with your contribution
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

Copyright
=========

Copyright (c) 2011 Stefano Verna. See LICENSE.txt for
further details.

