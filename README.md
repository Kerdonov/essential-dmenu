dmenu - dynamic menu
====================
dmenu is an efficient dynamic menu for X.


Requirements
------------
In order to build dmenu you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


Running dmenu
-------------
See the man page for details.

Fork
----
This version of dmenu has received minor tweaks. The patches applied are:

* lineheight
* linesbelowprompt and fullwidth

The versions of the patches and patch files are in the root directory of this repo.
