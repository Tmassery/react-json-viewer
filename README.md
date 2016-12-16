# react-json-viewer-size
React Component for View JSON in beautiful tabular format. See images below.
Note: Images are little old. From version 1.0.7, we show colors too.


[![NPM version][npm-image]][npm-url]
[![npm download][download-image]][download-url]

[npm-image]: http://img.shields.io/npm/v/react-json-viewer-size.svg?style=flat-square
[npm-url]: https://npmjs.org/package/react-json-viewer-size
[download-image]: https://img.shields.io/npm/dm/react-json-viewer-size.svg?style=flat-square
[download-url]: https://npmjs.org/package/react-json-viewer-size

# Install

[![react-json-viewer-size](https://nodei.co/npm/react-json-viewer-size.png?downloads=true)](https://npmjs.org/package/react-json-viewer-size)

# Demo

[http://Tmassery.github.io/react-json-viewer-size](http://Tmassery.github.io/react-json-viewer-size/)

# JSFiddle Example

[http://jsfiddle.net/Tmassery/61fwqcg5/](http://jsfiddle.net/Tmassery/61fwqcg5/)

# What

![alt pic](https://raw.githubusercontent.com/Tmassery/react-json-viewer-size/master/pic1.png)
![alt pic](https://raw.githubusercontent.com/Tmassery/react-json-viewer-size/master/pic2.png)

# Use

```
var JSONViewer = require('react-json-viewer-size');
var todos = [{
 task: "Learn React",
 done: true
},{
 task:"Write Book",
 done: false
}];


<JSONViewer json={todos}></JSONViewer>
```

# Develop
```
npm install
npm run server
open http://localhost:8912
```