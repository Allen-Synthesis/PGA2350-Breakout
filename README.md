# PGA2350-breakout
### Breakout board for the Pimoroni PGA2350 for Eurorack breadboard development

![PXL_20240910_170328695](https://github.com/user-attachments/assets/0a13265c-7ed1-4494-a1c9-59230b055330)

At the time I'm writing this, the only development board I can find for sale which utilises the B variant of the RP2350 *and* breaks out all of the extra ADCs it offers, is the [Pimoroni PGA2350](https://shop.pimoroni.com/products/pga2350?variant=42092629229651), however it is not a breadboard compatible.  
This board adapts the PGA2350 to allow it to be used for Eurorack development with a breadboard, breaking out all required connections including routing Eurorack power from a standard header to pin headers which can be connected to a breadboard's rails using jumper wire.  
The USB connections are arranged so that an [Adafruit USB Micro-B Breakout Board](https://www.adafruit.com/product/1833) (also sold by [Pimoroni](https://shop.pimoroni.com/products/adafruit-usb-micro-b-breakout-board?variant=821196557)) can be soldered directly to the board.

*NOTE: The first PCB order for these boards was tested on 10/09/2024 and appears to all work as expected. Not every GPIO has been tested, however the design is likely functional. Aesthetic improvements for version 1.1 (outlined below) have not yet been applied*

Pending changes based on version 1.0:
1. Increment version to 1.1
1. Alter pin header footprints to remove square pad for 1x2, 1x5, and 2x5
1. Add JLC PCB order number text to the back
1. Use consistent . or / in version date
1. Remove J12 reference text
1. Add ground stitching vias
1. Use arrow to label PGA2350 and then use internal space to show orientation
1. Measure the USB breakout board and adjust position so that the edge is flush
1. Add lines between the labels and pins for rest of the headers as has been done for the GPIO headers
1. Add artwork to the back (and front?) to make use of the space
