Bash Settings
=============
A central place to keep by bash shell settings. There are two version:

* bash_profile_osx
* bash_profile_linux

The files should mostly be the same, save for a few differences e.g. the OS X version
sets the default editor to TextMate.

To setup the bash settings:

* Create a directory in your home directory e.g. 
    mkdir ~/bash-settings
* Grab the code:
    git clone url
* Create a symlink to the appropriate settings file in your home directory
    # In OS X
    ln -s ~/bash-settings/bash_profile_osx ~/.bash_profile
    
    # In linux
    ln -s ~/bash-settings/bash_profile_linux ~/.bash_profile

TODO
----
1. Check the linux filenames for the bash settings - not sure whether it should be .bash_rc
