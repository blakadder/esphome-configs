# Blakadder's ESPHome Configurations

My esphome configs for public projects

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/S6S650JEK) &emsp; <a href="https://paypal.me/tasmotatemplates"><img src="https://img.shields.io/static/v1?logo=paypal&label=&message=Donate via PayPal&color=slategrey"></a>

## athom_ps01.yaml

Confguration for Athom mmWave Human Presence sensor (PS01). Available from AliExpress

### Changelog

- now stores mmWave configuration values as it is supposed to
- add PIR delay in substitutions to configure no occupancy delay on PIR motion and Occupancy sensors
- change Occupancy sensor logic to make sense
- smaller steps for configuration options allowing finer grained configurations
- sliders with too many options switched to number boxes
- remove on trigger delay of 50ms for even more responsive triggers (no idea why they're set in the first place)
- set button to internal since its a reset button and hard to reach
- remove factory reset button from HA device card, if you really want to reset use the web UI or the button
- disabled by default these diagnostic sensors: MAC address, SSID)
