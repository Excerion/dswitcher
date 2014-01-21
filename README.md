dswitcher
=========

Dmenu-based window switcher for EWMH-compliant X11 window managers. It presents a list of all windows, regardless of their workspace and whether or not they're minimized, in a vertical dmenu instance. You can filter by typing in any part of the window title, but in addition, each window is assigned a number, which is prepended in the list. Simply typing that number works as well. This feature was taken from Musca and is similar to Ratpoison/Stumpwm.

### Dependencies
- dmenu;
- wmctrl;
- an EWMH-compliant X11 window manager.

### Installation
- Resolve the dependencies. In Debian, this means:

`sudo apt-get install dmenu wmctrl`
- copy dswitcher to your PATH;
- bind some key to the dswitcher command. xbindkeys is recommended. If you're using a desktop environment, it probably provides a feature for this already. Look in your DE's settings.
