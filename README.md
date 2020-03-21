# Blockchain Explorer based on Steem-JS (For private steemd based Blockchains)
Steem explorer is a client-side block explorer for steem-like blockchains. It uses Steem-JS API to query users, posts, and transactions directly to the seed nodes.

![](https://cdn.steemitimages.com/DQmbHSzTWPQHwZkFJr185z3P7ZQhwVZtWDPmS8y37Gm9HuG/image.png)

## Clone
``` bash

sudo apt-get install git nano screen

cd ~

git clone https://github.com/nnnarvaez/weku-explorer.git 

cd weku-explorer/
```

## Config
Change the configuration file `src/config.js` with the symbols and rpc_node of the blockchain.

## Build Setup

``` bash

# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

## TO-DO:

**Fix pagination for new query pages**

* account votes
* account tranfers

Currently first paginates then filters resulting in empty paginated pages.
# weku_explorer
