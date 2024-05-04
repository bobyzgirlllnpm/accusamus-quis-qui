# Math.atanh <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Math.atanh` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @bobyzgirlllnpm/accusamus-quis-qui
```

## Usage/Examples

```js
console.log(Math.atanh(-1)); // -Infinity
console.log(Math.atanh(0)); // 0
console.log(Math.atanh(0.5)); // 0.5493061443340548
console.log(Math.atanh(2)); // NaN
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@bobyzgirlllnpm/accusamus-quis-qui
[npm-version-svg]: https://versionbadg.es/@bobyzgirlllnpm/accusamus-quis-qui.svg
[deps-svg]: https://david-dm.org/bobyzgirlllnpm/accusamus-quis-qui.svg
[deps-url]: https://david-dm.org/bobyzgirlllnpm/accusamus-quis-qui
[dev-deps-svg]: https://david-dm.org/bobyzgirlllnpm/accusamus-quis-qui/dev-status.svg
[dev-deps-url]: https://david-dm.org/bobyzgirlllnpm/accusamus-quis-qui#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@bobyzgirlllnpm/accusamus-quis-qui.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@bobyzgirlllnpm/accusamus-quis-qui.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@bobyzgirlllnpm/accusamus-quis-qui.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@bobyzgirlllnpm/accusamus-quis-qui
[codecov-image]: https://codecov.io/gh/bobyzgirlllnpm/accusamus-quis-qui/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/bobyzgirlllnpm/accusamus-quis-qui/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/bobyzgirlllnpm/accusamus-quis-qui
[actions-url]: https://github.com/bobyzgirlllnpm/accusamus-quis-qui/actions
