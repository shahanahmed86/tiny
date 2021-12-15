# @shahanahmed86/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@shahanahmed86/tiny.svg)](https://www.npmjs.com/package/@shahanahmed86/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@shahanahmed86/tiny.svg)](https://www.npmjs.com/package/@shahanahmed86/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @shahanahmed86/tiny
```

## Usage

```js
const tiny = require("@shahanahmed86/tiny");
tiny("So much space!");
//=> "Somuchspace!"
tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
