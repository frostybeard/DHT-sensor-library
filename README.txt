This is an Arduino library for the DHT series of low cost temperature/humidity sensors. 

To download. click the DOWNLOADS button in the top right corner, rename the uncompressed folder DHT. Check that the DHT folder contains DHT.cpp and DHT.h. Place the DHT library folder your <arduinosketchfolder>/libraries/ folder. You may need to create the libraries subfolder if its your first library. Restart the IDE.

This is a celsius-only version, with the heat index conversion and Celsius <-> Fahrenheit conversions removed to save space on the Arduino.
(the heat index and Fahrenheit isn't really used outside the USA)

Setting things up:

1. remember to modify the pin number definition to the pin you are using on your Arduino.
2. remember to set the correct DHT sensor type. (DHT11, DHT21, DHT22)

Use a 1000 ohm resistor to pull up your data pin. Connect the resistor between the data pin and VCC. 

Google is your friend. There are many schematics and pictures showing how to wire it up.
