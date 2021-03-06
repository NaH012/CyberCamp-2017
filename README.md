# CyberCamp-2017 #
This is the code as well as the schematic for the electronics portion of CyberCamp 2017

# Set Up #
This circuit is powered by a Wemos D1 Mini, a Maxium7219, an anode 8x8 LED matrix, a button, and a buzzer
![The Circuit](/Cyber-Camp.jpg?raw=true)

## Programming the Board ##
--------------------------------------
### Getting the Arduino IDE ###
1. Go [Arduino][arduino-download] and go to Download Arduino IDE
2. Install the program


### Adding the ESP8266 chip to your Arduino IDE ###
1. Go to file -> preferences
2. Copy this url "http://arduino.esp8266.com/stable/package_esp8266com_index.json" into the "additional boards manager URLs" dialog box
3. Go to tools -> boards: -> board manager, find the esp8266 board, click on it and click install


### Add the files to control the LED matrix ###
1. You will need to download [Max72xxPanel][max-download] and [Adafruit_GFX][gfx-download] as a zip file
2. Then in the Arduino IDE go to Sketch > Include Library > Add .zip library
3. Select the zip files you just downloded


### Uploading to the board ###
Make sure the chip is selected, you can do this by going to tools > board > Wemos D1 R2 & mini

### Mac Not Recognizing the Board ###
Got to [sparkfun][ftdi] and follow the instructions to install the drivers

# Contact #
Weston Shakespear: westonshakespear@gmail.com
Mike Julander: 1110mdj@gmail.com

# Second Screen #
![The Second Circuit](/Cyber-Camp-Dual-Matrix.jpg?raw=true)

[ftdi]: https://learn.sparkfun.com/tutorials/how-to-install-ftdi-drivers/mac
[arduino-download]: https://www.arduino.cc/en/Main/Software "Download the Arduino IDE"
[max-download]: https://github.com/markruys/arduino-Max72xxPanel/archive/master.zip "Download Max72xxPanel library"
[gfx-download]: https://github.com/adafruit/Adafruit-GFX-Library "Download Adafruit GFX Graphics Library"
