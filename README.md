# vue-nodewebkit

> A simple Webpack for Vue and Node-Webkit starter projects.

### Usage

**For use in a web browser:**

``` bash
$ npm install
$ npm run start-w
```

**For use as a desktop app:**

``` bash
$ npm install -g nodewebkit
$ npm install
$ npm run start-d
```

### What's Included

- `npm run start-w`: Launch Web App ([localhost:8080](http://localhost:8080/))- Webpack + `vue-loader` with proper config for source maps & hot-reload.

- `npm run start-d`: Launch Desktop App -  Webpack + `vue-loader` + Node Webkit.

- `npm run build`: Run a single build - dist/build.js

- `npm run build-w`: Watch for changes to files and run a build on file save - dist/build.js