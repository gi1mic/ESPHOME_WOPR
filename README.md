# ESPHOME_WOPR
19" Rack mount display similar to WOPR - the computer from the film War Games (1983) for Home Assistant

This is a modified version of https://www.printables.com/model/1167457-1u-rack-mount-wopr-leds-enclosure built using ESPHOME allowing control from Home Assistant

The display uses three 4x8x8 MAX7219 LED Matrix Modules providing a resolution of 96 x 8 pixels
 
I used this 3D printed remix of the 19" rack mount https://www.printables.com/model/1216518-improved-1u-rack-mount-wopr-leds-enclosure as it fitted the MAX7219 Digit Displays I was using.
  
For a controller I used a simple ESP8266 WEMOS board I had handy but any of the supported ESPHOME platforms should work if you change the board type and SPI pins.

Extensions to the code include the ability to display the time, text message, change the brightness and turn the display on/off via homassistant.


 Note: This is  work in progress and I still need to tweak the WOPR display code as the effect is OK but not exactly what I want.


 You can find the pixelmix font at https://fontsaddict.com/font/pixelmix-regular.html the ttf file needs to be put in the /config/esphome directory.
