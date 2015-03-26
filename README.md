FontGen
=======

A simple utility application that takes a TTF file and converts it
into a .pgm along with a text file describing which character maps to
which coordinates.

Arguments
---------

* `TTFFILE`: filename of the .ttf (or any other format supported by freetype)

* `SIZE`: size of the font (in pixel?!)

* `BORDER`: an border that is left around each glyph, useful when one
wants to add effects such as shadow or a black border

* `IMAGEWIDTH`: width of the resulting image

* `IMAGEHEIGHT`: height of the temporary image (ugly, but needed at the moment)

* `UNICODES`: optional list of characters that shall be generated, default is the whole font
