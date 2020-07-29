# Image to LCD

A companion project for Inkplate_Raw_Bitmap (https://github.com/Kongduino/Inkplate_Raw_Bitmap).

Drag and drop an image onto the window, it will create two files after resizing the image if necessary to fit within the Inkplate 6 (800x600).

1. A header file that can be added to the project and displayed with `display.drawBitmap3Bit();`.
2. A vaguely custom bitmap file (width and height as uint16, then pixels, a nibble per) that can be stored on an SD card and displayed on demand.

Works great but don't expect bells and whistles.

