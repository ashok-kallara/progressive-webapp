# PWA POC

A Progressive Web App built with Polymer base on https://github.com/PolymerLabs/zuperkulblog-progressive

## Setup

* Install node and npm
* Install gulp with npm --```npm install -g gulp```
* Install bower with npm -- ```npm install -g bower```
* Install node http-server with npm -- ```npm install -g http-server```

```
git clone https://github.com/PolymerLabs/zuperkulblog-progressive
cd progressive-webapp
npm install && bower install
gulp
http-server ./dist -S -C cert.pem -p <PORT>
```
