Sandy Seventies Speedboat MediaGoblin Theme
===========================================

[![screenshot](https://media.jpope.org/mgoblin_media/media_entries/557/Screenshot_-_11302014_-_023001_PM.medium.png)](https://media.jpope.org/u/jpope/m/mediagoblin-theme-sandy-seventies-speedboat-3b67/)

This theme is included with the current [MediaGoblin](http://mediagoblin.org) release.

During your MediaGoblin install or update, you should have run:

*Install:* `git submodule init && git submodule update`  
*Update:* `git submodue update`  

which should have pulled in this theme to `./extlib/sandyseventiesspeedboat/`.

To use this theme, edit your `mediagoblin_local.ini` file with:  
`theme = sandyseventiesspeedboat`  
and run to link the theme assets  

    $ ./bin/gmg assetlink  

and restart your instance.

####About this theme

This theme uses a few bits of [Skeleton](http://www.getskeleton.com) and the [Font Awesome](http://fontawesome.io) icon font.

The name _Sandy Seventies Speedboat_ is thanks to @[aether](https://blahblahblah.indyshop.org/aether)'s notice here: [Link](https://blahblahblah.indyshop.org/aether/comment/-Z5gahTpRbGVpTlYizQZkA) - *(sorry for the dead links, seems that pump instance is no longer online...)*

If you find any issues with the theme, please file a report on the [issue tracker](https://github.com/jpope777/sandyseventiesspeedboat-mg/issues).

#### Old Usage prior to being included with defaut install

***This section is no longer needed but, being kept here for older installs. This theme is not guaranteed to work with older versions of MediaGoblin. Actually, it most likely will not...***

Navigate to your MediaGoblin directory and if it isn't present, create the directory `./user_dev/themes/` and navigate into the newly created directory.

Clone this theme with:

    git clone https://github.com/jpope777/sandyseventiesspeedboat-mg.git sandyseventiesspeedboat

Edit your `mediagoblin_local.ini` file to use this theme:  
`theme = sandyseventiesspeedboat`

You'll need to link the theme assets by running:

    ./bin/gmg assetlink

And finally, restart your MediaGoblin and enjoy.
