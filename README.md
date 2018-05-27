# Tap Streak - For Arduino

[Tap Streak](https://play.google.com/store/apps/details?id=com.vexingmedia.tapstreak) originally started as a mobile game for both iOS and Android. Since then I started tinkering with an Arduino and needed a project, that's when I discovered the [Trellis](https://www.adafruit.com/product/1616) by Adafruit.

The premis of Tap Streak is simple, there is a grid of squares, a pattern of squares is lit up in a specific sequence, once the sequence has played through, the player replicates the sequence by pressing on the squares on the screen. The same concept can be done physically using the Trellis. The sequence is displayed through the LEDs, and the player replicates the sequence by pressing on the rubber pad, pretty simple.

## Requirements
1. [Arduino Nano V3.0 ATmega328P](https://store.arduino.cc/usa/arduino-nano) - You can pick these up on [Amazon](https://www.amazon.com/gp/product/B06XFSZW6C) from a third party manufacturer for cheaper.
2. [Adafruit Trellis Monochrome Driver PCB](https://www.adafruit.com/product/1616)
3. [Silicone Elastomer 4x4 Button Keypad](https://www.adafruit.com/product/1611)
4. 16 x 3mm LEDs - [Blue LEDs from Adafruit](https://www.adafruit.com/product/780) work great
5. Mini A to B USB cable
6. [STL files for a 3D printed case](https://github.com/adafruit/Adafruit_Trellis)
7. [Trellis library](https://github.com/adafruit/Adafruit_Trellis_Library) for Arduino
8. [Instructions](https://learn.adafruit.com/adafruit-trellis-diy-open-source-led-keypad/overview) for wiring and connecting the Trellis
