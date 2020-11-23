# homebridge-lifx-lan-client

[![npm package](https://nodei.co/npm/homebridge-lifx-lan-client.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/homebridge-lifx-lan-client/)

LiFx LAN platform plugin for [Homebridge](https://github.com/nfarina/homebridge).

This platform uses only the LiFx LAN protocol.

Currently supports:
- On/Off
- Brightness
- Kelvin
- Hue (Color models only)
- Saturation (Color models only)

# Installation

1. Install homebridge using: npm install -g homebridge
2. Install this plugin using: npm install -g homebridge-lifx-lan
3. Update your configuration file. See the sample below.

# Updating

- npm update -g homebridge-lifx-lan-client

# Configuration

Configuration sample:

 ```javascript
"platforms": [
    {
        "platform": "LifxLan",
        "name": "LiFx",
        "ignoredDevices" : ["abcd1234561", "efabcd6721"]
    }
]

```


# Credits

- Marius Rumpf for his awesome [lifx-lan-client](https://github.com/node-lifx/lifx-lan-client) library
