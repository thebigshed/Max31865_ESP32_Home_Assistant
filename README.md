# Max31865_ESP32_Home_Assistant
My ESP32 compatible connected to PT1000 probe
The interface is a MAX31865, when bought the reference resistor was 470 ohms to match a PT100.
So if you want to use a PT1000 on it you need to change RREF to a 4.7K (4K7). It is a SMD so a little fiddly but not bad.
I also installed the solder links to configure it for 2 wire probe.

On the ESP I soldered the link to enable the RGB LED for future use with the idea of the colour representing the temperature.

