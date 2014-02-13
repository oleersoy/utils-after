# SUIT utilities: after

[![Build Status](https://secure.travis-ci.org/suitcss/utils-after.png?branch=master)](http://travis-ci.org/suitcss/utils-after)

A SUIT collection of utility classes for offsetting elements.

Read more about [SUIT's design principles](https://github.com/suitcss/suit/).

## Installation

* [Component(1)](http://component.io/): `component install suitcss/utils-after`
* [Bower](http://bower.io/): `bower install --save suitcss/utils-after`
* Download: [zip](https://github.com/suitcss/utils-after/zipball/master)

## Available classes

* `u-afterXofY` (numerous) - Specify the proportional offset before an object.

`X` must be an integer less than `Y`.

`Y` can be any of the following numbers: 2, 3, 4, 5, 6, 8, 10, 12.

### Plugins

Utilities that can be limited to specific Media Query breakpoints.

* `v1-u-afterXofY` - To use at the first Media Query breakpoint.
* `v2-u-afterXofY` - To use at the second Media Query breakpoint.
* `v3-u-afterXofY` - To use at the third Media Query breakpoint.

## Usage

Please refer to the README for [SUIT utils](https://github.com/suitcss/utils/)

## Testing

Install [Node](http://nodejs.org) (comes with npm).

```
npm install
```

To generate an un-preprocessed build (i.e., you want to use your own tooling and configure variables).

```
npm run build
```

To generate a standalone, preprocessed build.

```
npm run build-standalone
```

To generate the testing build.

```
npm run build-test
```

Basic visual tests are in `test.html`.

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 8+
