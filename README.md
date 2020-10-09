![backbone-es6](https://i.imgur.com/KKkgP8P.png)

[![Backbone](https://img.shields.io/badge/backbone-1.3.3-yellowgreen.svg?style=flat)](https://github.com/jashkenas/backbone)
[![Documentation](http://docs.typhonjs.io/typhonjs-backbone/backbone-es6/badge.svg)](http://docs.typhonjs.io/typhonjs-backbone/backbone-es6/)
[![Code Style](https://img.shields.io/badge/code%20style-allman-yellowgreen.svg?style=flat)](https://en.wikipedia.org/wiki/Indent_style#Allman_style)
[![License](https://img.shields.io/badge/license-MPLv2-yellowgreen.svg?style=flat)](https://github.com/typhonjs-backbone/backbone-es6/blob/master/LICENSE)
[![Gitter](https://img.shields.io/gitter/room/typhonjs/TyphonJS.svg)](https://gitter.im/typhonjs/TyphonJS)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fstephanbit%2Fbackbone-es6.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fstephanbit%2Fbackbone-es6?ref=badge_shield)

[![Build Status](https://travis-ci.org/typhonjs-backbone/backbone-es6.svg?branch=master)](https://travis-ci.org/typhonjs-backbone/backbone-es6)
[![Dependency Status](https://www.versioneye.com/user/projects/56eb95004e714c003625c72a/badge.svg?style=flat)](https://www.versioneye.com/user/projects/56eb95004e714c003625c72a)

Backbone supplies structure to JavaScript-heavy applications by providing models with key-value binding and custom events, collections with a rich API of enumerable functions, views with declarative event handling, and connects it all to your existing application over a RESTful JSON interface.

backbone-es6 is a fork of Backbone (https://github.com/jashkenas/backbone) converting and modularizing it into idiomatic ES6. The impetus for this fork is to experiment with modernizing and making Backbone easier to modify in a granular fashion. In particular the [Parse JS SDK](http://www.parse.com) previously also was a fork of Backbone, but with the 1.6+ SDK release the Backbone API was unceremoniously removed. backbone-es6 provides the base for [backbone-parse-es6](https://github.com/typhonjs-backbone-parse/backbone-parse-es6) which provides a solution for Backbone dependent Parse users. 

Another reason for backbone-es6 is supporting end to end documentation via ESDoc for ES6 frameworks and apps built on top of backbone-es6. An integrated build and testing NPM module [typhonjs-npm-build-test](https://github.com/typhonjs-node-npm-scripts/typhonjs-npm-build-test) including several plugins for ESDoc along with a complete integrated set of Gulp tasks, [typhonjs-core-gulptasks](https://github.com/typhonjs-node-gulp/typhonjs-core-gulptasks) provide documentation generation across multiple modules / source roots via JSPM along with ESLint and several JSPM & NPM tasks.

backbone-es6 uses [JSPM](http://www.jspm.io) / [SystemJS](https://github.com/systemjs/systemjs) for dependency management and bundling distributions. For an example of using JSPM / SystemJS directly with backbone-es6 & Backbone.localStorage including typhonjs-core-gulptasks support please see these demo repos:

- https://github.com/typhonjs-demos/backbone-es6-localstorage-todos
- https://github.com/typhonjs-demos/electron-backbone-es6-localstorage-todos  (Electron desktop version)

Update (05/12/16): backbone-es6 has been updated with the latest Backbone 1.3.3 changes. After Backbone is updated to 1.4 and backbone-es6 is updated a full test suite will also be created including Nightmare JS / browser testing. The final planned upgrade is to then modify backbone-es6 completing full modularization by splitting it into several separate repos which will still be collected and exposed through this repo. This final separation will allow each component of Backbone to potentially be used independently with minimal dependencies including server side usage. 

This repository contains several pre-packed downloads in the `dist/` directory. There are AMD, CJS, and Global distributions. The "global-inclusive" bundle includes the latest jQuery (2.2.3) and Underscore (1.8.3) libraries.

API documentation can be generated locally and is also found online here:
http://docs.typhonjs.io/typhonjs-backbone/backbone-es6/

For original Backbone Docs, License, Tests, pre-packed downloads, see:
http://backbonejs.org

To suggest a feature or report a bug:
https://github.com/typhonjs-backbone/backbone-es6/issues

Many thanks to DocumentCloud & all Backbone contributors.

Backbone (c) 2010-2015 Jeremy Ashkenas, DocumentCloud and Investigative Reporters & Editors

backbone-es6 (c) 2015-present Michael Leahy, TyphonRT Inc. 

backbone-es6 may be freely distributed under the MPL v2.0 license.


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fstephanbit%2Fbackbone-es6.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fstephanbit%2Fbackbone-es6?ref=badge_large)