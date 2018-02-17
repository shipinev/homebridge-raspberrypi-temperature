# homebridge-tinker-board-temperature
[![npm version](https://badge.fury.io/js/homebridge-tinker-board-temperature.svg)](https://badge.fury.io/js/homebridge-tinker-board-temperature)

A Homebridge plugin for Tinker Board to show CPU temperature

## Configuration
```
"accessories": [{
    "accessory": "TinkerBoardCPUTemperature",
    "name": "Tinker Board CPU Temperature"
}]
```
If you want temperature value timing update, you can set 'updateInterval' attribute (milliseconds).   
```
"accessories": [{
    "accessory": "TinkerBoardCPUTemperature",
    "name": "Tinker Board CPU Temperature",
    "updateInterval": 1000
}]
```
