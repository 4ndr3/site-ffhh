#### How to build the Freifunk Hamburg Firmware
    
    git clone git://github.com/freifunk-gluon/gluon.git            # Get the official Gluon repository
    cd gluon
    git clone git://github.com/freifunkhamburg/site-ffhh.git site  # Get the Freifunk Hamburg site repository
    make update                                                    # Get other repositories used by Gluon
    make                                                           # Build Gluon

Please see [the official Gluon repository](https://github.com/freifunk-gluon/gluon) for an in-depth explanation of the build process.


#### Gluon versions used for specific Hamburg Freifunk Firmware builds

- 0.5: v2014.3
- 0.4.2: v2014.2
 - note: no gluon fork used anymore
- 0.4.1: v2014.2-hh
 - equal to official gluon v2014.2 + ffhh specific patches
- 0.4a: v2014.1a
 - equal to official gluon v2014.1 + ffhh specific patches 
