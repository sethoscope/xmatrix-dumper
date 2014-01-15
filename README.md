# xmatrix dumper

Here you wil find a modified version of xmatrix, one of the hacks from
jwz's [XScreenSaver](http://www.jwz.org/xscreensaver/).  Instead of
drawing to the screen, it writes each frame to a file in XPM format.

To build this, get a copy of XScreenSaver, replace xmatrix.c with
this one, and build as normal.  You probably don't want to install it
system-wide though, because this would be an awful screensaver.

I hacked this together in a few hours, in order to make a boot
animation fon an Android device (whose display has far more pixels
than my computer's), and I thought it might be of use to someone.

Although the original works on OSX, this probably doesn't yet.
Patches are welcome.
