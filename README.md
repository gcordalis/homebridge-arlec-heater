# homebridge-arlec-heater

`homebridge-arlec-heater` is a plugin for HomeBridge which allows you to control your arlec Heater.

## Features

- Set Power State
- Set Temperature
- Set High or Low Mode (via oscillate setting in HomeKit)
- Lock/Unlock Physical Controls

### Supported Models

- CV0645

## Installation

If you are new to Homebridge, please first read the Homebridge [documentation](https://www.npmjs.com/package/homebridge).

Install homebridge:

```sh
npm install -g homebridge
```

Install this plugin:

```sh
npm install -g homebridge-arlec-heater
```

## Configuration

Add the accessory in `config.json` in your home directory inside the homebridge directory.

Example configuration:

```js
"accessories": [
  {
    "accessory": "arlecHeater",
    "name": "arlec Heater",
    "id": "XXXXXXXXXXXXXXXXXXXX",
    "key": "XXXXXXXXXXXXXXXX",
    "ip": "X.X.X.X"
  }
]
```
