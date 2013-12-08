   CM11
===========


Getting Started
---------------

To get started with Cyanogenmod Project, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the AOSP trees, use a command like this:

    repo init -u git://github.com/XNovathor/manifest.git -b cm-11.0

Then to sync up:

    repo sync

To build :

    . build/envsetup.sh
    lunch cm_"device_name"-eng                       (kumquat, pepper, lotus, nypon)
    make otapackage
