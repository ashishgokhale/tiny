# @ashishgokhale/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@ashishgokhale/tiny.svg)](https://www.npmjs.com/package/@ashishgokhale/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@ashishgokhale/tiny.svg)](https://www.npmjs.com/package/@ashishgokhale/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @ashishgokhale/tiny
```

## Usage

```js
const tiny = require("@ashishgokhale/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1