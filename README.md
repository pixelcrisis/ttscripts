<p align="center">
  <img src="https://s3.amazonaws.com/assets.turntable.fm/images/index/logo.png"/>
  <br>
  <br><b>turntable scripts</b>
  <br>a collection of community
  <br>created styles and scripts for turntable.fm</br>
</p>

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/fluteds/turntable-styles/graphs/commit-activity) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) [![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)

## What is this?

This repo contains community made styles such as themes and additional addons for turntable.fm.

## Usage

These themes and addons are designed to be used with [Stylus](https://github.com/stylus/stylus) or [turnStyles](https://github.com/pixelcrisis/turnstyles).

## Contributing

Since this repo is Open Sourced, pull requests are highly reccommended.

### How to Submit Themes

#### Method One

- Fork the repo
- Add your theme/addon files
- Open a [pull request](http://makeapullrequest.com)

#### Method Two

- [Open an issue](https://github.com/fluteds/ttScripts/issues/)
- Link the source of your theme/addon
- Paste the theme/addon code in `Code Blocks`

## Credit

When submitting a theme, you can put a css comment before the code stating who made the theme.

```css
/* ==UserStyle==
@name         Name of Theme
@version      1.0.0
@description  Description of Theme
@namespace    https://github.com/fluteds
@author       Your Name
@homepageURL  https://github.com/fluteds/ttScripts
@supportURL   https://github.com/fluteds/ttScripts/issues/
@match        https://turntable.fm/*
@updateURL    https://raw.githubusercontent.com/fluteds/ttscripts/link-to-your-theme-location
==/UserStyle== */

body::before {
    content: "Hello World";
}
```

For submitting a Javascript addon.

```js
// ==UserScript==
// @name         Name of Addon
// @namespace    http://tampermonkey.net/
// @version      1.0.0
// @description  Description of Addon
// @author       Your name
// @match        https://turntable.fm/*
// @grant        none
// ==/UserScript==

// Your script
console.log('Hello World');
```
