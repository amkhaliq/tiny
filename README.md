# @abdulkhaliq94/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@bamblehorse/tiny.svg)](https://www.npmjs.com/package/@abdulkhaliq94/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@bamblehorse/tiny.svg)](https://www.npmjs.com/package/@abdulkhaliq94/tiny)

Removes all spaces from a string.

## Install
```
$ npm install @abdulkhaliq94/tiny
```
## Usage
```js
const tiny = require("@abdulkhaliq94/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
