Shopify Express Example App
===========

#### NOTE : use for development purposes only!

Table of Contents
-----------------
- [Build and expose](#build-and-expose)

Build and expose
-----------
```sh
yarn && yarn dev:node
```

Next expose VPS tunnel via SSH
```sh
ssh -R 3000:localhost:3000 -i <KEY> -N <HOSTNAME>@<IP_ADDR>
```
