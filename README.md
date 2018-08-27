# SVG 3D Builder

[![npm version](https://img.shields.io/npm/v/svg-3d-builder.svg?style=flat-square)](https://www.npmjs.com/package/svg-3d-builder)

<div align=left>
    <img src="https://media.giphy.com/media/5zvQqld4fwqoh3m3Nd/giphy.gif" height="200" style="display:inline-block" align="center"/>
    <img src="https://media.giphy.com/media/1oFtOzT1JQQObvCDqC/giphy.gif" height="200" style="display:inline-block" align="center"/>
    <img src="https://media.giphy.com/media/LYuSClXbN76s0rQdIJ/giphy.gif" height="200" style="display:inline-block" align="center"/>
</div>

This framework aims at creating 3d models with **SVG** and to provide a concise API. It is purely developed with concepts of two-dimensions.
One of its essential implementations is **Bezier** in both curve and surface. 
It is one thing to describe them with mathematic equations, but another thing to illustrate them with computer graphics.

See [online exhibition](https://libcafe.com/3d/index.html) developed by the framework and its [source code](https://github.com/captainwz/svg-3d-builder/tree/master/demo/exhibition).

## Start
You can either start it in [traditional way](https://github.com/captainwz/svg-3d-builder/blob/master/dist/svg-3d-builder.min.js)
```html
<script src="./svg-3d-builder.min.js"></script>
```
Or embark your development with `ES6`
```shell
npm install --save svg-3d-builder
```
```javascript
import Builder from 'svg-3d-builder';
```
Make sure there is an svg element described in your document
```html
<html>
    <head>
    </head>
    <body>
        <svg id="graph" width="500" height="500">            
        </svg>
    </body>
</html>
```
And see your simplest work by adding these codes
```javascript
Builder
.select('#graph')
.drawLine('M 0 0 0 l 100 0 0')
.action();
```

**Of course you can see [code examples](https://github.com/captainwz/svg-3d-builder/tree/master/code_examples.md) before building sophisticated works by yourself.**


## API
You also need to look up the [API document](https://github.com/captainwz/svg-3d-builder/tree/master/api.md).

## Lisence
Apache

## Other
[postscript](https://libcafe.com/2018/08/25/3d-builder/)


