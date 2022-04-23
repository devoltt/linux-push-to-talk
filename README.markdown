
**WARNING**: This project has long-since been unmaintained and is very unlikely to still be usable as-is on modern versions of Gnome.  Good luck, though!


# Push-to-talk for Linux

This gnome application allows one to assign a key (by default *F12*) that will unmute one's microphone while pushed.

## Dependencies

 - setuptools
 - pygtk
 - Xlib

On Ubuntu, this is as easy as running ``sudo apt-get install python3-setuptools python-gtk2 python3-xlib``.

## Installation

 1. Run ``sudo python3 setup.py install``.
 2. Run ``ptt``.
 
If the application immediately closes with the message "You must log-out and log-in again for your system tray icon to appear.", log-out and log-back in again; a system settings change was required.

## Changing the Push-to-talk Key

 1. Right-click on the microphone icon in your system tray.
 2. Click 'Set Key'.
 3. Press the key you'd like to use.

