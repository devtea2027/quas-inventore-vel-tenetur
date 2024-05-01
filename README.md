# @devtea2027/quas-inventore-vel-tenetur <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@devtea2027/quas-inventore-vel-tenetur');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@devtea2027/quas-inventore-vel-tenetur
[npm-version-svg]: https://versionbadg.es/inspect-js/@devtea2027/quas-inventore-vel-tenetur.svg
[deps-svg]: https://david-dm.org/inspect-js/@devtea2027/quas-inventore-vel-tenetur.svg
[deps-url]: https://david-dm.org/inspect-js/@devtea2027/quas-inventore-vel-tenetur
[dev-deps-svg]: https://david-dm.org/inspect-js/@devtea2027/quas-inventore-vel-tenetur/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@devtea2027/quas-inventore-vel-tenetur#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@devtea2027/quas-inventore-vel-tenetur.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@devtea2027/quas-inventore-vel-tenetur.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@devtea2027/quas-inventore-vel-tenetur.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@devtea2027/quas-inventore-vel-tenetur
[codecov-image]: https://codecov.io/gh/inspect-js/@devtea2027/quas-inventore-vel-tenetur/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@devtea2027/quas-inventore-vel-tenetur/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@devtea2027/quas-inventore-vel-tenetur
[actions-url]: https://github.com/devtea2027/quas-inventore-vel-tenetur/actions
