# ext-esp-grow
## Project Description
 This personal project was an Espressif ESP8266/ESP32 based indoor plant monitoring system that was designed to get myself fimilar with the ESP8266 and ESP32 chipset.
 
## esp-grow (Rev A)
This was an esp8266 based automatic plant monitor system.
The system will monitor the capacitive soil sensor, tenperature and humidity and activate the water pump accordingly.
The system hosts its own webpage to give the user status of the plants progress.

### Design Files
### Electrical Design Files
This project contains the Altium Designer schematic and pcb files, wiring diacrams and code for an esp8266 based indoor plant monitoring system.

This system is comprised of three main blocks:
1) Wemos D1 - ESP-12F; I really like working with this form factor since it has an esp8266 with a breadboard header and a CH340G
2) ESP-Grow_OLED_Rev_A: custom 2 layer pcb with a generic SSD1306 128x64 I2C monochrome OLED screen and a tack button seated under the screen.      Basically a screen button.
3) ESP-Grow_OLED_Main_A: The motherboard. A custom 4 Layer pcb with all the connectors, power rails and leds.

## esp32-grow (Rev B)
This was an esp32 based automatic plant monitor system.
The system will monitor the capacitive soil sensor, tenperature and humidity and activate the water pump accordingly.
The system hosts its own webpage to give the user status of the plants progress.

![TopView](https://github.com/Elipsit/esp-grow-2.0/blob/main/electrical/pics/esp-grow-2.0-top.png)

### Custom Soil Sensor
![sens_stake](https://github.com/Elipsit/esp-grow/blob/master/Rev%20B/pics/sens_Stake.png)

## Schematic
[schematic](https://github.com/Elipsit/esp-grow-2.0/blob/main/electrical/schematic/ESP_Grow_Main_V2-2021-04-18.PDF)




