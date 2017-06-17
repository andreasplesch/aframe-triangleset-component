## aframe-triangleset-component

[![Version](http://img.shields.io/npm/v/aframe-triangleset-component.svg?style=flat-square)](https://npmjs.org/package/aframe-triangleset-component)
[![License](http://img.shields.io/npm/l/aframe-triangleset-component.svg?style=flat-square)](https://npmjs.org/package/aframe-triangleset-component)

A triangleset geometry primitive for A-Frame

For [A-Frame](https://aframe.io).

### API

| Property | Description | Default Value |
| -------- | ----------- | ------------- |
|          |             |               |

### Installation

#### Browser

Install and use by directly including the [browser files](dist):

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/0.5.0/aframe.min.js"></script>
  <script src="https://unpkg.com/aframe-triangleset-component/dist/aframe-triangleset-component.min.js"></script>
</head>

<body>
  <a-scene>
    <a-entity triangleset="foo: bar"></a-entity>
  </a-scene>
</body>
```

<!-- If component is accepted to the Registry, uncomment this. -->
<!--
Or with [angle](https://npmjs.com/package/angle/), you can install the proper
version of the component straight into your HTML file, respective to your
version of A-Frame:

```sh
angle install aframe-triangleset-component
```
-->

#### npm

Install via npm:

```bash
npm install aframe-triangleset-component
```

Then require and use.

```js
require('aframe');
require('aframe-triangleset-component');
```
