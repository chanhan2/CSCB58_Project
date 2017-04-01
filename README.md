# CSCB58_Project
Painting With DE2 Using Verilog

Using the VGA output from the DE2 Cyclone IV E 
board to paint 2-d pixelated images.

The inputs to draw the bounderies for the paint
tool are switching on SWITCH 16-13 on before 
running the program. And the keys to move the cursor 
are KEYS 3-0 to paint. To toggle through the available 8-bit 
colours are SWITCHES 16-13.

NOTE:
The KEYS used to recieve input from the DE2 board will have 
a slight delay due to slowing down the clock cycle from
CLOCK_50 of 50mhz to 10mhz to allow for user control of the 
painting cursor.

Created by Hanson Chan student ID 1002436562 and Arvic Landrito student ID 1002641590.
