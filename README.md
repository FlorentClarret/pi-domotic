# Configure my rapsberry home automation lab

## Purpose

This ansible playbook allow me to configure a raspberry pi from scratch to test my home automation stuff. Currently, I'm using jeedom, zigbee2mqtt and a HAT microphone.

## What is done in this playbook

1. Use raspi-config in order to configure the memory-split, timezone, hostname and expand file system...
2. Install the squid-deb-proxy-client and update the nodes. I have not a very good internet connection speed, that's why I deployed a squid-deb-proxy on my server at home.
3. Deploy and configure ufw.
4. Install my personal configuration and aliases. It's a bit useless, but I like to have my home configured.
5. Install and configure zigbee2mqtt

## Hardware

* Raspberry pi 2, 3 or 3B+ depending on what I'm doing with my other pis.
* Texas Instrument CC2531 USB stick.
* Philips hue bridge (replaced most of the time by the CC2531 usb stick, but I still use it for testing purpose)
* ReSpeaker 4-Mic Array.

## Related links

* [Zigbee2mqtt](https://www.zigbee2mqtt.io/)
* [Jeedom](https://www.jeedom.com/site/en/)