Agile Toolkit Icon Set Compass Extension
==========================

A way to use the awesome [Agile Toolkit Icon Set](http://www.agiletech.ie/blog/128x16x16) within your project.

Installation
============

From the command line:

    sudo gem install atk_icons

Installing into an existing Rails project:

    # add atk_icons to your Gemfile
    gem 'atk_icons'

    # require atk_icons from your Compass configuration file (compass.rb)
    require 'atk_icons'

    # import the extension into your scss/sass file
    @import atk_icons

    # copy atk_icons.png to your public/images directory
    cd public/images && curl http://bit.ly/iHd2XF

Or create a new project:

    compass create <project_name> -r atk_icons --using atk_icons

    #import the extension into your scss/sass file
    @import "atk_icons"

Usage Example
=============

    # for a list of all the icons available, see http://www.agiletech.ie/blog/128x16x16

    .button.delete
      /* this will add an :after pseudo-selector with the specified icon
      @include atk-icon-pseudo("basic-ex")

    .button.add span.icon
      /* you can also set the icon to a sub-element
      @include atk-icon("basic-plus")

The previous SASS will result in the following CSS:

    .button.delete {
      position: relative;
      padding-left: 15px;
    }

    .button.delete:before {
      background-image: url('/images/atk_icons.png');
      display: inline-block;
      height: 16px;
      width: 14px;
      background-position: -2px -64px;
      content: "";
      position: absolute;
      left: 0px;
      top: 0px;
    }

    .button.add span.icon {
      background-image: url('/images/atk_icons.png');
      display: inline-block;
      height: 16px;
      width: 14px;
      background-position: -2px 0px;
    }

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

