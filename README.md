# \<t-pax-input\>


[![Build Status](https://travis-ci.org/nxtComponent/t-pax-input.svg?branch=master)](https://travis-ci.org/nxtComponent/t-pax-input)  [![Coverage Status](https://coveralls.io/repos/github/nxtComponent/t-pax-input/badge.svg)](https://coveralls.io/github/nxtComponent/t-pax-input)

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



## Coverage Test


Install `web-component-tester`, `istanbul` and `web-component-tester-istanbul` global level

```

$ npm i -g web-component-tester@4.3.1 istanbul https://github.com/t2ym/web-component-tester-istanbul/tarball/0.10.1
```

Install coveralls in repository

```

$ npm install coveralls --save-dev

```
