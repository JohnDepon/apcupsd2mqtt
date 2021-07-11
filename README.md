# apcupsd2mqtt

> Publish values from apcupsd to MQTT 🔌🔋

[![mqtt-smarthome](https://img.shields.io/badge/mqtt-smarthome-blue.svg)](https://github.com/mqtt-smarthome/mqtt-smarthome)
[![NPM version](https://badge.fury.io/js/apcupsd2mqtt.svg)](http://badge.fury.io/js/apcupsd2mqtt)
[![Dependency Status](https://img.shields.io/gemnasium/hobbyquaker/apcupsd2mqtt.svg?maxAge=2592000)](https://gemnasium.com/github.com/hobbyquaker/apcupsd2mqtt)
[![Build Status](https://travis-ci.org/hobbyquaker/apcupsd2mqtt.svg?branch=master)](https://travis-ci.org/hobbyquaker/apcupsd2mqtt)
[![XO code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg)](https://github.com/sindresorhus/xo)
[![License][mit-badge]][mit-url]

This is a fork of https://github.com/cyberjunky/node-apcupsd - modified to follow 
[mqtt-smarthome architectural proposal](https://mqtt-smarthome/mqtt-smarthome).

## Fork updates
Added option to pass specific `apcupsd.conf` config to `apcupsd2mqtt`.
Example `apcupsd2mqtt -a /etc/apcupsd.conf`

This change allows to run multiple instances of apcupsd2mqtt accessing multiple running instances of apcupsd in order to monitor multiple UPS devices.

## Install

`$ sudo npm install -g apcupsd2mqtt`

## Usage

`$ apcupsd2mqtt --help`

## License

MIT

Copyright (c) 2017 Sebastian Raff    
Copyright (c) 2014 Ron Klinkien

[mit-badge]: https://img.shields.io/badge/License-MIT-blue.svg?style=flat
[mit-url]: LICENSE
