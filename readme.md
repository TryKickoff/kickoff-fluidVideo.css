# @kickoff/fluidvideo.css
> Simple fluid-width videos using CSS only

[![npm version](https://badge.fury.io/js/@kickoff/fluidvideo.css.svg)](https://badge.fury.io/js/kickoff-fluidVideo.css)

[![NPM](https://nodei.co/npm/kickoff-fluidVideo.css.png)](https://nodei.co/npm/kickoff-fluidVideo.css/)

## Install

```
npm install @kickoff/fluidvideo.css --save
```

## Usage
With scss and the [npm-sass](https://www.npmjs.com/package/npm-sass) or similar importer

```scss
@import "@kickoff/fluidvideo.css/index"
```

```html
<div class="fluidVideo">
	<iframe class="fluidVideo-item" src="..."/>
</div>

<!-- add modifier for 4:3 aspect ratio -->
<div class="fluidVideo fluidVideo--4-3">
	<iframe class="fluidVideo-item" src="..."/>
</div>
```
