# Ruby WiFi Location Changer
* Automatically change location when wifi connection changes in Mac OS X
* Allows having different IP settings depending on the wifi SSID

Simplified location changer based on http://tech.inhelsinki.nl/locationchanger/

Forked from https://github.com/rimar/wifi-location-changer

## Installation
Edit locationchanger and change _ninja_ to your SSID

    cp locationchanger /usr/local/bin
    cp LocationChanger.plist ~/Library/LaunchAgents/
    launchctl load ~/Library/LaunchAgents/LocationChanger.plist
