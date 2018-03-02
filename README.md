# extensometer
All weather wireless extensometer, with user display and data recording.

Starting from the ground up.  Using a JSN-SR04T water proof ultrasonic sensor, and feeding data to an SD card
on an arduino shield.  Haven't decided yet if I'll use a MAX7219 CWG 8 digit 7 segment display, or a 16x2 LCD
display.  I think the 8 digit display will work better outside, but I've never used one before, so there's
some testing to do yet.

So far the sketch records distances and saves data to the SD card, using an uno and an SD shield.

Things to implement:
  -real time clock
  -display
  -user controls
  -convert from uno to nano arduino
