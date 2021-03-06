# PWA POC

A Progressive Web App built with Polymer base on https://github.com/PolymerLabs/zuperkulblog-progressive. Changes being:
* Removed dependency on Google Cloud SDK
* Added support for
  * push using Google Firebase
  * Camera support
  * Vibrate
* Enabled TLS as it's needed for hardware APIs

## Setup

* Install node and npm
* Install gulp with npm --```npm install -g gulp```
* Install bower with npm -- ```npm install -g bower```
* Install node http-server with npm -- ```npm install -g http-server```

## Running it

```
cd progressive-webapp
npm install && bower install
gulp
http-server ./dist/static -S -C cert.pem -p <PORT>
```
