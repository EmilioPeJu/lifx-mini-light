# LIFX MINI LIGHT SCRIPT
Simple script to control a lifx light given its IP. Please run the script with
 parameter '-h' for getting some help.
Note that this has been tested using a lifx mini bulb, therefore it does not
 implement all the features that the non-mini bulb has.

# Why?
There are many scripts/libraries to control lifx bulbs, but all of them, use
 autodiscovery, which works by sending broadcast traffic. This script intends
 to control a lifx bulb without having to send broadcast traffic, as that might
 not be allowed in some networks.
