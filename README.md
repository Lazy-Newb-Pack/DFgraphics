DFgraphics
==========

A collection of Dwarf Fortress graphics packs, configured for [Starter Packs]
(http://lazynewbpack.com/).

Current targeted version:  DF 0.40.24

Each graphics pack is set up to use the features of PyLNP 0.11a to save space by
omitting duplicate or vanilla files.  With the exception of ASCII-Default, they
also use [TWBT](https://github.com/mifki/df-twbt) to the greatest extent practical.

Graphics packs must consist of more than a tileset and color scheme, as PyLNP has
alternative management methods for those which are more flexible and take less space.
Tilesets which need not be installed with very pack - i.e. most ASCII-based tilesets -
are stored as a singe special-case graphics packs.

In practise, many shared files such as mouse images, standard curses tilesets,
and Meph's vanilla TwbT overrides can be placed in `LNP/Tilesets` to save space.
However this package is entirely self-contained, so any single graphics pack
will work without any further configuration or extra files.
