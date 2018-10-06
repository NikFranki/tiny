# @nikfranki/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@franki/tiny.svg)](https://www.npmjs.com/package/@franki/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@franki/tiny.svg)](https://www.npmjs.com/package/@franki/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @franki/tiny
```

## Usage

```js
const tiny = require("@franki/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1