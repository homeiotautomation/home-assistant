# home-assistant Config
# homeiotautomation - Home-Assistant Config

Hardware - [Raspberry Pi3](https://www.microsoft.com/en-ca/store/d/raspberry-pi-3-board-and-16gb-10class-with-noobs/8zgwhg9k487r?activetab=pivot%3aoverviewtab) expanded to 16GB 

Software on the Pi - [HassIO](https://www.home-assistant.io/hassio/) - [Home Assistant](https://home-assistant.io/) 

Home Assistant configuration files (YAMLs)

Dynamic DNS via [NOIP](https://www.noip.com)

SSL via [Lets Encrypt](https://letsencrypt.org)

**Devices:**
* Cisco Meraki MX64.
* Cisco Meraki MS220-8P.
* Cisco Meraki MR33.
* Ubiquiti Networks EdgeRouter™ X.
* SmartThings Hub for ZWAVE and Zigbee control.
* Philips Hue Hub Gen2.
* Logitech Harmony Hub.
* Broadlink RM PRO to control Portable Aircon, IR fans & Aukey 433mhz RF.
* Amazon Echo DOT Online Voice Control(AE).
* Google Home Mini Online Voice Control(GHM).
* Cisco ATA VIOP Freephoneline. No fee landline.
* Mixture of Hue Colored lights and Daylight white Cree bulbs.
* Nanoleaf Aurora.
* Yamaha Receiver.
* Nexus Player.
* Amazon Fire TV.
* Bravia 4k 43 XBR X800E.
* Chromecast.
* Chromecast Audio.
* AukeyOutlets - Cheap $7 RF outlet control!
* Vansky LED Controlled by Aukey Outlets.
* Wemo Switches - Control AirPurifier and Humidifier
* Nest Camera.
* Nest Protect
* Xiaomi Smart Home Aqara Human Motion Sensor
* Xiaomi Smart Door and Windows Sensor
* Emulated Hue pushes all Light, Switch, Group and scene for Amazon echo control.
* NUVISION Tablet running Vox Commando AKA **JARVIS AI** for Offline voice control. - *Disabled* - Need a mini PC and better far field array MIC.

**Automations:**

* JARVIS Welcomes family member when they arrive home. WIP - *Disabled*
* JARVIS Welcomes family as a whole when everyone arrives at the same time - WIP - *Disabled*
* GHM - JARVIS voice welcomes family member when they arrive home.
* GHM - JARVIS voice announce when a family member leaves home.
* MQTT - Bridge HA to SmartThings Hub - Xiaomi Sensors 
* Sunset, Turn on Front Door Light with voice notification in GHM.
* Sunset, Turn on Ambiance Lighting TV, Window, China Cabinet, Hallway LED and Nanoleaf Aurora with voice notification in GHM.
* Midnight, Turn off Ambiance Lighting except Hallway LED with voice notification in GHM.
* Dusk, Turn off Hallway LED and my Daughters Room Light.
* Frondoor/Dining motion, turns on Frontdoor and Dining light, no motion within 15min lights turns off.
* Hallway motion, turns on hallway light from 7am to 11pm no motion within 1min lights turns off.
* Master Bedroom motion, turns on bedroom light from sunset to 11pm, no motion within 10min lights turns off.
* Daughters Bedroom motion, turns on bedroom from 7am to 11pm, no motion within 5min lights turns off
* HA Alarm - Perimiter, Home and Away. Intruder notification alarm via GHM.
* HA Alarm - Arm Home Mode 12:30am
* Send text to cell phone when alarm is truggered


**Voice Control: via Google Home Mini(GHM), Amazon Echo(AE), JARVIS - *Disabled*, SIRI via[Homebridge] - (WIP)**

* Turn all lights, light groups On/Off with voice confirmation
* Change light color, hue, saturation and brightness with voice confirmation
* TV On/Off, Channels, volume by 2 or 5 increment/decrement
* Entertainment - TV, Nexus Player and Yamaha Receiver
* Turn On/Off Nanoleaf Aurora and effects.
* Arm alarm via GHM.
* Request Weather info
* Request Time

```
