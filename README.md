wifi-weather-station [![Build Status](https://travis-ci.org/openhomeautomation/wifi-weather-station.svg)](https://travis-ci.org/openhomeautomation/wifi-weather-station)
====================

This is the code for the "Make a WiFi Weather Station With Arduino and the CC3000 chip" article on the Open Home Automation website. The article is about remotely measuring temperature & humidity with Arduino and the CC3000 WiFi chip.

The repository contains three folders:
- interface: the interface to display the data on your computer
- sensor_test: the Arduino sketche to test the DHT sensor
- wifi_weather_station: the main Arduino sketch of the project

You can find the corresponding article on the Open Home Automation website:

http://www.openhomeautomation.net/arduino-wifi-cc3000/

Make sure Node.js is installed. If it gives error...see below steps you should follows.
You can install these packages

1. Install Node.js fom nodeja.org
2. Check packages once you installed from Node command prompt
3. Install Node packages : npm install <package_name>
4. Package "arest"   : npm install arest
5. Package "express" : npm install express
6. Package "jade"    : npm install jade
7. See still you getting error in your screen, so and so package missing
8. Follow no. 3 point above
9. You are done
10. That will install the required modules for Node.JS. 
11. Then, type: node app.js


You should be greeted by a message: Listening on port 3000

After that, go to this URL in your favorite web browser: http://localhost:3000

Wait a bit so that the board can send the first set of data, and this is what you should see:

If you can see the data being displayed, congratulations, your WiFi weather station is online! 

ref. link: https://learn.adafruit.com/wifi-weather-station-arduino-cc3000/using-the-weather-station

