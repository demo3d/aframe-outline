# A-Frame Outline component

aframe-outline is an A-Frame Outline component.

![screenshot](./screenshot.png "screenshot")

## Properties

### aframe-deferred-renderer

| Properties  | type   | Default Value | Description |
| ----------- | ------ | ------------- | ----------- |
| thickness   | number | 0.003         | Outline thickness. |
| color       | color  | '#000'        | Outline color. |
| alpha       | number | 1.0           | Outline alpha. |

## Browser

### How to use

```
<head>
  <script src="./libs/aframe.min.js"></script>
  <script src="./build/aframe-outline.min.js"></script>
</head>

<body>
  <a-scene outline>
    <a-entity position="0 10 20">
      <a-camera></a-camera>
    </a-entity>

    <a-entity geometry="primitive:sphere"></a-entity>

    <a-entity light="type:directional;color:#888" position="-10 -10 -10"></a-entity>
  </a-scene>
</body>
```

## NPM

### How to install

```
$ npm install aframe-outline
```

### How to build

```
$ npm install
$ npm run all
```

### How to load

```
require('aframe');
require('aframe-outline');
```