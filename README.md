# DIY Color LED Strip

I created this YouTube video to demonstrate how to set up this project:<br>
<insert link here>  --- Will be uploaded soon!
  <br>
<br>
<b>To start this project, you will need:</b>
* Arduino compatible board
* NeoPixel LEDs (aka WS2812).  Sizes can be either 5mm or 8mm.
* Breadboard
* Jumper Cables

<b>If you need to purchase these items, you can use these links: </b><br>
Generic NeoPixel LEDs: https://amzn.to/3yeQehN     You can also get the LEDs from Adafruit: https://www.adafruit.com/product/1938 <br>
I highly recommend getting an Arduino Starter Kit if you haven't already: (Arduino, Breadboard, Cables, and MUCH more):  https://amzn.to/3ip5ORy <br>
<b>Individual items: </b> <br>
Arduino (clone):  https://amzn.to/3gryOIo    Breadboard:  https://amzn.to/3B6WqtV    Jumper Cables:  https://amzn.to/3koqhHq <br>
<br>
<b>Project steps:</b><br>
Adafruit is a great resource for learning and picking up great products.
This page covers the 5mm LEDs:  https://www.adafruit.com/product/1938
And this page covers everything you need to know about working with NeoPixels: https://learn.adafruit.com/adafruit-neopixel-uberguide/the-magic-of-neopixels<br>
<br>
If you have never used Arduino before, do these first:<br>
Install Arduino Integrated Development Environment as shown here:<br>
WINDOWS: https://www.arduino.cc/en/Guide/Windows<br>
MAC: https://www.arduino.cc/en/Guide/macOS<br>
Upload the "Blink" example sketch as shown here to verify correct configurations:<br>
https://www.arduino.cc/en/Tutorial/BuiltInExamples/Blink<br>
<br>
You will need to download and install the NeoPixel Library from Adafruit as shown here:<br>
https://learn.adafruit.com/adafruit-neopixel-uberguide/arduino-library-installation<br>
<br>
After installing NeoPixel Library, open the "strandtest" example.<br>
Verify the pin assignment (default is Pin 6) matches your setup.<br>
Change the number of LEDs to match your setup (default is 10).<br>
<br>
<b>Circuit Setup:</b><br>
Place your LEDs into the breadboard.  The LEDs have two short legs and two long legs.  With the short legs on the left, the pins are as follows:<br>
1 - Data IN<br>
2 - +5V<br>
3 - GROUND<br>
4 - Data OUT<br>
<br>
Pin 4 from the first LED should be in the same electrical row as Pin 1 as the second LED.  This pattern should be followed for all LEDs in the sequence.<br>
For each LED, connect pin 2 to the RED rail and pin 3 to the BLUE rail on the Breadboard.<br>
Connect a cable from the RED rail to the "5V" pin on the Arduino<br>
Connect a cable from the BLUE rail to any "GND" pin on the Arduino<br>
Connect a cable from Pin 1 on the first LED in the sequence to Pin 6 (or whichever pin you chose) on the Arduino  <br>
  <br>
After verifying the code and circuit have been setup correctly, upload the sketch to your board and your LEDs should come to life!<br>
  
