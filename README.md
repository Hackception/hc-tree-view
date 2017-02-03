# \<hc-tree-view\>  [![Travis](https://img.shields.io/travis/rust-lang/rust.svg?style=flat-square)](https://github.com/Hackception/hc-tree-view/)

An optimized tree-view based on a flat data structure.

## Browser Support

[![Build Status](https://saucelabs.com/browser-matrix/stramel.svg)](https://saucelabs.com/beta/builds/556b2791a7da4a9397951969625607be)

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
