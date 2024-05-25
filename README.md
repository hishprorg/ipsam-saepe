# @hishprorg/ipsam-saepe <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@hishprorg/ipsam-saepe');
const Eval = require('@hishprorg/ipsam-saepe/eval');
const Range = require('@hishprorg/ipsam-saepe/range');
const Ref = require('@hishprorg/ipsam-saepe/ref');
const Syntax = require('@hishprorg/ipsam-saepe/syntax');
const Type = require('@hishprorg/ipsam-saepe/type');
const URI = require('@hishprorg/ipsam-saepe/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@hishprorg/ipsam-saepe
[npm-version-svg]: https://versionbadg.es/ljharb/@hishprorg/ipsam-saepe.svg
[deps-svg]: https://david-dm.org/ljharb/@hishprorg/ipsam-saepe.svg
[deps-url]: https://david-dm.org/ljharb/@hishprorg/ipsam-saepe
[dev-deps-svg]: https://david-dm.org/ljharb/@hishprorg/ipsam-saepe/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@hishprorg/ipsam-saepe#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@hishprorg/ipsam-saepe.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hishprorg/ipsam-saepe.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hishprorg/ipsam-saepe.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hishprorg/ipsam-saepe
[codecov-image]: https://codecov.io/gh/ljharb/@hishprorg/ipsam-saepe/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@hishprorg/ipsam-saepe/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@hishprorg/ipsam-saepe
[actions-url]: https://github.com/hishprorg/ipsam-saepe/actions
