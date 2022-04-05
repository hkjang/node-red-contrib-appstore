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
msg.func = 'app';
// msg.func = 'list';
// msg.func = 'search';
// msg.func = 'privacy';
// msg.func = 'developer';
// msg.func = 'suggest';
// msg.func = 'similar';
// msg.func = 'reviews';
// msg.func = 'ratings';

msg.appId  = '553834731';
// msg.devId  = '284882218';

msg.ratings  = true;

// msg.collection = store.collection.TOP_FREE_IPAD,
// msg.category = store.category.GAMES_ACTION,
// msg.num = 2

// msg.term = 'panda';
// msg.num = 2;
// msg.page = 3;
// msg.country  = 'us';
// msg.lang = 'lang';

// msg.appId  = 'com.midasplayer.apps.candycrushsaga';
// msg.page = 1;
return msg;
```
