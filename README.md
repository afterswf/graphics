# AwayJS Graphics

This is [Mesmotronic](https://mesmotronic.com)'s fork of [awayjs/graphics](https://github.com/awayjs/graphics) for
[AfterSWF](https://github.com/afterswf/embed), published as [`@afterswf/graphics`](https://www.npmjs.com/package/@afterswf/graphics).
Its fixes are listed in [AfterSWF's README](https://github.com/afterswf/embed#more-advanced-as3-content).

It keeps the original package names in its imports, so install it, and any other afterswf packages you use, under
their original names with npm aliases:

```sh
npm install @awayjs/graphics@npm:@afterswf/graphics
```

[![Build Status](https://travis-ci.org/awayjs/graphics.svg?branch=dev)](https://travis-ci.org/awayjs/graphics)

Dependency for AwayJS applications requiring graphical output: contains data structures for shapes and textures, and interface descriptions for additional APIs such as material and animator data.

## Documentation

[Official AwayJS Documentation](https://awayjs.github.io/docs/graphics)

## AwayJS Dependencies

* core

## Internal Structure

* animators<br>
Interface APIs for animator classes

* base<br>
Interface APIs for graphics dependents, and root classes for core graphics functionality

* draw<br>
Drawing API for sequential stroke and fill drawing commands

* elements<br>
Data classes for graphical elements such as triangle / line collections

* events<br>
Events for graphics classes

* image<br>
Image data wrappers for binary / compressed and 2D / Cubic images

* managers<br>
(to be moved to materials module)

* materials<br>
(to be moved to materials module)

* parsers<br>
Library parsers for image classes

* pick<br>
Collision object

* textures<br>
Data classes for textures that wrap image data sources

* utils<br>
Helper classes for Bitmap / Image conversion and / or generation