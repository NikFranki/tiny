# @NikFranki/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@NikFranki/tiny.svg)](https://www.npmjs.com/package/@NikFranki/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@NikFranki/tiny.svg)](https://www.npmjs.com/package/@NikFranki/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @NikFranki/tiny
```

## Usage

```js
const tiny = require("@NikFranki/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1