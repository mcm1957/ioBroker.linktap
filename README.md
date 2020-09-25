![Logo](admin/Logo_small.png)
# ioBroker.LinkTap

In Development -- Please do not install this adapter 

-- copy from iobroker template -- to be replaced
[![NPM version](http://img.shields.io/npm/v/iobroker.template.svg)](https://www.npmjs.com/package/iobroker.template)
[![Downloads](https://img.shields.io/npm/dm/iobroker.template.svg)](https://www.npmjs.com/package/iobroker.template)
![Number of Installations (latest)](http://iobroker.live/badges/template-installed.svg)
![Number of Installations (stable)](http://iobroker.live/badges/template-stable.svg)
[![Dependency Status](https://img.shields.io/david/Author/iobroker.template.svg)](https://david-dm.org/Author/iobroker.template)
[![Known Vulnerabilities](https://snyk.io/test/github/Author/ioBroker.template/badge.svg)](https://snyk.io/test/github/Author/ioBroker.template)

[![NPM](https://nodei.co/npm/iobroker.template.png?downloads=true)](https://nodei.co/npm/iobroker.template/)

**Tests:**: [![Travis-CI](http://img.shields.io/travis/Author/ioBroker.template/master.svg)](https://travis-ci.org/Author/ioBroker.template)
-- endcopy

## ioBroker.LinkTap

Control your garden irrigation with the LinkTap Wireless Water Timer

## Installation
Was developed under Node.js 12. So it is recommended to use this version at least.

## Settings
Create Api key at https://www.link-tap.com/#!/api-for-developers with your LinkTap credentials.

Please enter the username and API key in the configuration.
All connected gateways and taplinkers will be retrieved after the adapter is started. The retrieval can be done again at the earliest after 5 minutes.
The interval for retrieving the status information of the devices is every minute.

## Changelog

### 0.0.1
* (Smart-Gang) initial release

## License
MIT License

Copyright (c) 2020 Author <author@mail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.