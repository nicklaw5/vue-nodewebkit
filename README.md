# vue-nodewebkit

> A simple Webpack starter kit for developing Vue and Node-Webkit projects.

### Usage

``` bash
$ npm install -g nw
$ git clone https://github.com/nicklaw5/vue-nodewebkit.git
$ cd vue-nodewebkit
$ npm install
```

**Note:** Windows users may need to run `$ npm install --no-bin-links` if an error is raised from `npm install`.

**To launch as a a web app:**
``` bash
$ npm run w-app
```

**To launch as a desktop app:**
``` bash
$ npm run d-app
```

### What's Included

- `npm run w-app`: Launch Web App ([localhost:8080](http://localhost:8080/)) - Webpack + Vue-Loader with hot-reload.
- `npm run d-app`: Launch Desktop App - Vue-Loader + Node Webkit.
- `npm run build`: Run a single build - dist/build.js
- `npm run build-watch`: Watch for changes to files and run a build on file save - dist/build.js

## Documentation

- **Vue:**  [http://vuejs.org/guide/](http://vuejs.org/guide/)
- **Vue-Loader:**  [https://github.com/vuejs/vue-loader](https://github.com/vuejs/vue-loader)
- **Webpack:**  [http://webpack.github.io/docs/](http://webpack.github.io/docs/)
- **Node-Webkit:**  [http://docs.nwjs.io/en/latest/](http://docs.nwjs.io/en/latest/)