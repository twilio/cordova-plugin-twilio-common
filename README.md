cordova-plugin-twilio-common 
================
[![NPM](https://img.shields.io/npm/v/cordova-plugin-twilio-common.svg)](https://www.npmjs.com/package/cordova-plugin-twilio-common) [![Build Status](https://travis-ci.org/twilio/cordova-plugin-twilio-common.svg?branch=master)](https://travis-ci.org/twilio/cordova-plugin-twilio-common)

> This plugin offers support of [twilio-common.js](https://github.com/twilio/twilio-common.js) package (and [AccessManager](https://www.twilio.com/docs/api/chat/guides/access-token-lifecycle) in particular) for [Apache Cordova](https://cordova.apache.org/)

# Usage
After this plugin installation [twilio-common.js](https://github.com/twilio/twilio-common.js) is available in your Cordova project using `TwilioCommon` accessor.  

Example of usage:
```
   var accessManager = new TwilioCommon.AccessManager(token);
```
