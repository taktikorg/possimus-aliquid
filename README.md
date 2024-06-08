# Number.isInteger <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Number.isInteger` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-@taktikorg/possimus-aliquid).

## Getting started

```sh
npm install --save @taktikorg/possimus-aliquid
```

## Usage/Examples

```js
console.log(Number.isInteger(-3)); // true
console.log(Number.isInteger(2 ** 54)); // true
console.log(Number.isInteger(2.3)); // false
console.log(Number.isInteger(Infinity)); // false
console.log(Number.isInteger("7")); // false
```

## Tests

Clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@taktikorg/possimus-aliquid
[npm-version-svg]: https://versionbadg.es/taktikorg/possimus-aliquid.svg
[deps-svg]: https://david-dm.org/taktikorg/possimus-aliquid.svg
[deps-url]: https://david-dm.org/taktikorg/possimus-aliquid
[dev-deps-svg]: https://david-dm.org/taktikorg/possimus-aliquid/dev-status.svg
[dev-deps-url]: https://david-dm.org/taktikorg/possimus-aliquid#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@taktikorg/possimus-aliquid.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@taktikorg/possimus-aliquid.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@taktikorg/possimus-aliquid.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@taktikorg/possimus-aliquid
[codecov-image]: https://codecov.io/gh/taktikorg/possimus-aliquid/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/taktikorg/possimus-aliquid/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/taktikorg/possimus-aliquid
[actions-url]: https://github.com/taktikorg/possimus-aliquid/actions
