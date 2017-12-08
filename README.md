About applicationname-plasmoid
==============================

A plasmoid for KDE plasma which shows the application name of the focused window.

Features:
  * Shows the application name of the focused windows
  * Shows the activity name if no window is focused
  * Optionally, it shows the window title (enable it in the settings dialog)
  * Optionally, it shows the application icon (enable it in the settings dialog)
  * A fixed width can be set through the settings dialog
  * Font style (bold/italic/underline), family and color are customizable too

## How to install

    $ zip applicationname.zip package -r
    $ plasmapkg -i applicationname.zip
    $ kbuildsycoc4

or

    $ mkdir build
    $ cd build
    $ cmake ../
    # make install

## Donate

Donations via [Liberapay](https://liberapay.com/ilpianista) or Bitcoin (1Ph3hFEoQaD4PK6MhL3kBNNh9FZFBfisEH) are always welcomed, _thank you_!

## License

LGPL
