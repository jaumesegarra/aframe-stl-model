## aframe-stl-model

[![Version](http://img.shields.io/npm/v/aframe-stl-model.svg?style=flat-square)](https://npmjs.org/package/aframe-stl-model)

A STL files component for A-Frame. (a fork of [darkwave/aframe-stl-model-component](https://github.com/darkwave/aframe-stl-model-component))

For [A-Frame](https://aframe.io).

### API

| Property | Description | Default Value |
| -------- | ----------- | ------------- |
|     src     |   a-asset-item ref       |              |

#### Installation

Install via npm:

```bash
npm install aframe-stl-model
```

Then require and use.

```js
import 'aframe';
require('aframe-stl-model');
```

```html
<a-scene>
	<a-assets>
		<a-asset-item response-type="arraybuffer" id="house" src="/house.stl"></a-asset-item>
	</a-assets>
		 	
	<a-entity stl-model="src: #house" scale="0.02 0.02 0.02" material="color: #f0f; roughness: 1; metalness: 0"></a-entity>
</a-scene>
```
