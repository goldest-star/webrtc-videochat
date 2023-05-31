Video chat using WebRTC
=========================

Peer-to-peer video chat that works. It's tuber-time!

## Features
* Video chat with up to 15 people (limited only by user interface)
* Buttons to selectively mute audio and turn off video
* Client and server written in a single language: JavaScript
* Supported without client software by browsers with [WebRTC](http://caniuse.com/#feat=rtcpeerconnection)

## Anti-Features
* Does not require client software
* Does not require a Google+ account
* Does not send video stream through a 3rd party
* Does not spike your CPU at 100% utilization

## Requirements
* [EasyRTC](https://www.npmjs.org/package/easyrtc)
* [Express](https://www.npmjs.org/package/express)
* [Handlebars](http://handlebarsjs.com/)
* [nconf](https://www.npmjs.org/package/nconf)
* [socket.io](https://www.npmjs.org/package/socket.io)
* [NodeJS](https://nodejs.org/)


## Configuration
The server port, debug level, and SSL settings are configured via the `settings.json` file. tubertc uses port 8080, debug mode, and HTTP by default.
