node-red-contrib-appstore
================

Node-RED node for app-store-scraper



## Install

To install the stable version use the `Menu - Manage palette - Install`
option and search for node-red-contrib-appstore, or run the following
command in your Node-RED user directory, typically `~/.node-red`

    npm install node-red-contrib-appstore

## wrapper appstore
Node.js module to scrape application data from the Google Play store
- https://github.com/facundoolano/app-store-scraper


## Sample Flow
You can make this json string into a flow by using the node-red flow import function.

- [sample.json](examples/sample.json)

## Params
```javascript
msg.func = 'reviews';
msg.id  = '553834731'

// msg.func = 'app';
// msg.appId = 'com.google.android.apps.translate'


return msg;
```
