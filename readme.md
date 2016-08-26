# kickoff-fluidVideo.css
> Simple fluid-width videos using CSS only

[![npm version](https://badge.fury.io/js/kickoff-fluidVideo.css.svg)](https://badge.fury.io/js/kickoff-fluidVideo.css)

[![NPM](https://nodei.co/npm/kickoff-fluidVideo.css.png)](https://nodei.co/npm/kickoff-fluidVideo.css/)

## Install

```
npm install kickoff-fluidVideo.css --save
```

## Usage
With scss and the [npm-sass](https://www.npmjs.com/package/npm-sass) or similar importer

```scss
@import "kickoff-fluidVideo.css/index"
```

```html
<div class="fluidVideo">
	<iframe src="..."/>
</div>

<!-- add modifier for 4:3 aspect ratio -->
<div class="fluidVideo fluidVideo--4-3">
	<iframe src="..."/>
</div>
```
