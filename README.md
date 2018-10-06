# @nikfranki/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@nikfranki/tiny.svg)](https://www.npmjs.com/package/@nikfranki/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@nikfranki/tiny.svg)](https://www.npmjs.com/package/@nikfranki/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @nikfranki/tiny
```

## Usage

```js
const tiny = require("@nikfranki/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1