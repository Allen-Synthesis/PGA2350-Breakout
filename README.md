# PGA2350-breakout
### Breakout board for the Pimoroni PGA2350 for Eurorack breadboard development

![image](https://github.com/user-attachments/assets/f13c7844-6c97-4d8e-98f1-39c315df7998)

At the time I'm writing this, the only development board I can find for sale which utilises the B variant of the RP2350 *and* breaks out all of the extra ADCs it offers, is the [Pimoroni PGA2350](https://shop.pimoroni.com/products/pga2350?variant=42092629229651), however it is not a breadboard compatible.  
This board adapts the PGA2350 to allow it to be used for Eurorack development with a breadboard, breaking out all required connections including routing Eurorack power from a standard header to pin headers which can be connected to a breadboard's rails using jumper wire.  
The USB connections are arranged so that an [Adafruit USB Micro-B Breakout Board](https://www.adafruit.com/product/1833) (also sold by [Pimoroni](https://shop.pimoroni.com/products/adafruit-usb-micro-b-breakout-board?variant=821196557)) can be soldered directly to the board.

*NOTE: The first PCB order for these boards arrived on 09/09/2024 but has not yet been tested. I would not recommend ordering boards while this message is present as they have not been tested*

![image](https://github.com/user-attachments/assets/68b4f18e-9988-44c4-aa9e-b8ee314470f0)

Pending changes based on version 1.0:
1. Increment version to 1.1
1. Alter pin header footprints to remove square pad for 1x2, 1x5, and 2x5
1. Add JLC PCB order number text to the back
1. Use consistent . or / in version date
1. Remove J12 reference text
1. Add ground stitching vias
1. Use arrow to label PGA2350 and then use internal space to show orientation
