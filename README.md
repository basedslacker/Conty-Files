# Conty-Files
Udev rules for steam controllers and VR, and the OpenRC modules config file needed for controller support.

The steam rules need to be placed in /lib/udev/rules.d.  Make sure your user is in both the plugdev and input group. 

The modules config files needs to be place in your /etc/openrc/conf.d directory.  I urge against just blindly plopping this file in without making sure you haven't already configured your modules yet, as you can really mess things up this way.  Instead, vim into existing file and manually add uinpt as seen in my example config.  You do not need to do this if you have not configured Slack for OpenRC.
