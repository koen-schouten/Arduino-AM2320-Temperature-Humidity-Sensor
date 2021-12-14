# Arduino-AM2320-Temperature-Humidity-Sensor

Program to read temperature and humidity data from a AM2320 sensor using an Arduino UNO.

AM2320 Pin 1 should be connected to 5V.

AM2320 Pin 2 should be connected to Analog 4 on Arduino.

AM2320 Pin 3 should be connected to GND.

AM2320 Pin 4 should be connected to Analog 5 on Arduino.

# Reading data 

The data is send by serial over USB to a PC. The data can be read using the following command in linux:

    sudo cat /dev/ttyACM0
