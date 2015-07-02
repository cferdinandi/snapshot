# Snapshot [![Build Status](https://travis-ci.org/cferdinandi/snapshot.svg)](https://travis-ci.org/cferdinandi/snapshot)
Simple image styling.

[Download Snapshot](https://github.com/cferdinandi/snapshot/archive/master.zip) / [View the demo](http://cferdinandi.github.io/snapshot/)

**In This Documentation**

1. [Getting Started](#getting-started)
2. [Installing with Package Managers](#installing-with-package-managers)
3. [Working with the Source Files](#working-with-the-source-files)
4. [Browser Compatibility](#browser-compatibility)
5. [How to Contribute](#how-to-contribute)
6. [License](#license)



## Getting Started

Compiled and production-ready code can be found in the `dist` directory. The `src` directory contains development code.

### 1. Include Snapshot on your site.

```html
<link rel="stylesheet" href="dist/css/snapshot.css">
```

Snapshot is [built with Sass](http://sass-lang.com/) for easy customization. If you don't use Sass, that's ok. The `css` folder contains compiled vanilla CSS.

The `_config.scss` and `_mixins.scss` files are the same ones used in [Kraken](http://cferdinandi.github.io/kraken/), so you can drop the `_snapshot.css` file right into Kraken without making any updates. Or, adjust the variables to suit your own project.

### 2. Add the markup to your HTML.

```html
<img class="img-circle" src="#">
<img class="img-border" src="#">
<img class="img-photo" src="#">
```

Add simple `.img-*` classes to any `img` element to add styling. You can combine classes for additional styling options. Mix-and-match as desired.

And that's it, you're done. Nice work!



## Installing with Package Managers

You can install Snapshot with your favorite package manager.

* **[NPM](https://www.npmjs.org/):** `npm install cferdinandi/snapshot`
* **[Bower](http://bower.io/):** `bower install https://github.com/cferdinandi/snapshot.git`
* **[Component](http://component.io/):** `component install cferdinandi/snapshot`



## Working with the Source Files

If you would prefer, you can work with the development code in the `src` directory using the included [Gulp build system](http://gulpjs.com/). This compiles, lints, and minifies code, and runs unit tests. It's the same build system that's used by [Kraken](http://cferdinandi.github.io/kraken/), so it includes some unnecessary tasks and Sass variables but can be dropped right in to the boilerplate without any configuration.

### Dependencies
Make sure these are installed first.

* [Node.js](http://nodejs.org)
* [Gulp](http://gulpjs.com) `sudo npm install -g gulp`

### Quick Start

1. In bash/terminal/command line, `cd` into your project directory.
2. Run `npm install` to install required files.
3. When it's done installing, run one of the task runners to get going:
	* `gulp` manually compiles files.
	* `gulp watch` automatically compiles files when changes are made and applies changes using [LiveReload](http://livereload.com/).



## Browser Compatibility

Because IE 8 and lower do not support the `border-radius` property, `.img-circle` will not work in those browsers.

Snapshot is fully supported by IE 9 and higher, and all modern browsers.



## How to Contribute

In lieu of a formal style guide, take care to maintain the existing coding style. Please apply fixes to both the development and production code. Don't forget to update the version number, and when applicable, the documentation.



## License

The code is available under the [MIT License](LICENSE.md).