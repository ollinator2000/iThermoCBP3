# iThermoCBP3
CraftbeerPi3 Plugin for iThermometer

## Features
 * Starts a threaded UDP Listening Server in Background
 * Adds a new configurable Sensor to Craftbeerpi 
   
# Introduction
This project utilize the ESP iThermometer Hardware ( see Special Note ) 
![Dashboard](img/dash.jpg)

This Plugin starts a UDP Listening Server in Background . The Listening Port is configurable inside Sensor Settings.

## !!Special Note
This Plugin is written for the [iThermometer Project](https://github.com/emilio77/IThermometer)
 
## Known issues
* CraftbeerPi cant Stop via Software Switch while using this Plugin. The Stop Routine isnt working correctly

## Roadmap
* Check Routine which shows some kind of alert when the Server hasnt received any package for a period of time
