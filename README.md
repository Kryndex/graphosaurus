# Graphosaurus

[![Build Status](https://travis-ci.org/frewsxcv/graphosaurus.svg)](https://travis-ci.org/frewsxcv/graphosaurus)

A three-dimensional static graph viewer.

## Build

1. Run `git clone https://github.com/frewsxcv/graphosaurus.git` to clone this repository
1. Install [node](http://nodejs.org/), [npm](https://www.npmjs.org/), and [grunt-cli](https://www.npmjs.org/package/grunt-cli)
1. Run `npm install` to install all the build requirements
1. Run `grunt` to build Graphosaurus. The resulting compiled JavaScript will be in `dist/` and the docs will be in `doc/`

## Third party libraries bundled with Graphosaurus

* [`three.js`](https://github.com/mrdoob/three.js/)
 * Used because writing WebGL is time consuming
 * [License](https://github.com/mrdoob/three.js/blob/master/LICENSE)

* [`TrackballControls.js`](https://github.com/mrdoob/three.js/blob/master/examples/js/controls/TrackballControls.js)
 * Used for graph movement/controls
 * [License](https://github.com/mrdoob/three.js/blob/master/LICENSE)

## Mascot

![gryposaurus](https://upload.wikimedia.org/wikipedia/commons/7/70/Gryposaurus-notabilis_jconway.png)

[John Conway](https://en.wikipedia.org/wiki/User:John.Conway)'s illustration of our glorious leader, the ~~[gryposaurus](https://en.wikipedia.org/wiki/gryposaurus)~~ graphosaurus.
