# NMEA2000 Simulator App

![Screen Shot with iKreate USB Interface.](https://github.com/digitalyacht/NMEA2000-Simulator-App/blob/main/Screen%20Shots/iKreate+Simulate%20App.jpg?raw=true)

Welcome to our NMEA2000 Simulator App repository. This simple but powerful web app, in conjunction with our iKreate USB interface, can simulate all PGNs or replay one of our raw NMEA2000 log files that all of our wireless NMEA2000 products can produce. 

Written in HTML5, the app uses Web Serial APIs, to access the iKreate's USB Serial port at 230400 baud. The iKreate sits on the NMEA2000, without claiming a CAN address and then transmits whatever PGNs are sent to it by the App, with the SRC address specified. This means it can recreate exact NMEA2000 network configurations and not simply send all PGNs from one CAN address.

This is the world's first multi-platform NMEA2000 Simulator program and whether you use Windows, LINUX, Mac OSX or Raspbian this simple app (single HTML file) which requires no installation, will allow you to simulate and recreate a wide variety of NMEA2000 networks.  

You might also want to consider our [NMEA2000 Display App](https://github.com/digitalyacht/NMEA2000-Display-App) that can be used with one of our iKonvert USB gateways to display and monitor the PGNs and Devices on an NMEA2000 network.

**WARNING** - simulating PGNs or replaying log files can negatively impact a vessel's normal NMEA2000 network and should only be done in a controlled workshop type environment. We recommend setting up a totally separate NMEA2000 network using one of our [NMEA2000 Starter Kits](https://digitalyacht.co.uk/product/cabling-kit/) and just connecting the iKreate, an iKonvert USB (if you wish to monitor the PGN data) and the NMEA2000 device you wish to demo or test.    
