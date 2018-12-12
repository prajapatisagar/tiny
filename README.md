# tiny
A tiny function that removes all spaces from a string.

@sagarprajapati/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@sagarprajapati/tiny.svg)](https://www.npmjs.com/package/@sagarprajapati/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@sagarprajapati/tiny.svg)](https://www.npmjs.com/package/@sagarprajapati/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @sagarprajapati/tiny
```

## Usage

```js
const tiny = require("@sagarprajapati/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
