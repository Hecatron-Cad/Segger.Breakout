# Segger Breakout

This is a simple kicad design for a breakout board for the JLink Segger.

  * https://www.segger.com/products/debug-probes/j-link/models/j-link-edu/

It also has pads for connecting an ESP32 ProS3, or a Rpi Pico 2040
To clone use
```sh
git clone --recurse-submodules https://github.com/Hecatron-Cad/Segger.Breakout.git
```

## VCC Pins

I've added a jumper for the VCC input to VTref on the segger.
some pages suggest not to connect it when the device is powered over usb, but I think this is incorrect.
Still I added a jumper just in case anyway

  * https://www.visualmicro.com/page/ESP32-Debugging.aspx
