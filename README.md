# vue-nodewebkit

> A simple Webpack for Vue and Node-Webkit starter projects.

### Usage

``` bash
$ git clone https://github.com/nicklaw5/vue-nodewebkit.git
$ cd vue-nodewebkit
$ npm install
```

**To launch as a a web app:**
``` bash
$ npm run start-web
```

**To launch as a desktop app:**
``` bash
$ npm run build
$ npm run start-desktop
```

### What's Included

- `npm run start-web`: Launch Web App ([localhost:8080](http://localhost:8080/)) - Webpack + Vueify with proper config for source maps & hot-reload.

- `npm run start-desktop`: Launch Desktop App -  Webpack + Vueify + Node Webkit.

- `npm run build`: Run a single build - dist/build.js

- `npm run build-watch`: Watch for changes to files and run a build on file save - dist/build.js