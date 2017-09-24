# Homebridge-samsungSmartTv

Samsung TV plugin for [Homebridge](https://github.com/nfarina/homebridge)

This allows you to control your Samsung Smart TV with HomeKit and Siri.

## Installation
1. Install homebridge using: npm install -g --unsafe-perm homebridge
2. Install this plugin using: npm install -g homebridge-samsungsmarttv
3. Update your configuration file. See `config-sample.json`.

## Important Notes
The TV API does not work when the TV is powered down, so on the plugin will send wake-on-lan command over ethernet to switch it on.

This plugin has 2 types, the first one is for TV power and the second one is for tv sound. See config.sample for more details
