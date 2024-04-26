# @wemnyelezxnpm/hic-non-exercitationem <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@wemnyelezxnpm/hic-non-exercitationem');
const Eval = require('@wemnyelezxnpm/hic-non-exercitationem/eval');
const Range = require('@wemnyelezxnpm/hic-non-exercitationem/range');
const Ref = require('@wemnyelezxnpm/hic-non-exercitationem/ref');
const Syntax = require('@wemnyelezxnpm/hic-non-exercitationem/syntax');
const Type = require('@wemnyelezxnpm/hic-non-exercitationem/type');
const URI = require('@wemnyelezxnpm/hic-non-exercitationem/uri');

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

[package-url]: https://npmjs.org/package/@wemnyelezxnpm/hic-non-exercitationem
[npm-version-svg]: https://versionbadg.es/ljharb/@wemnyelezxnpm/hic-non-exercitationem.svg
[deps-svg]: https://david-dm.org/ljharb/@wemnyelezxnpm/hic-non-exercitationem.svg
[deps-url]: https://david-dm.org/ljharb/@wemnyelezxnpm/hic-non-exercitationem
[dev-deps-svg]: https://david-dm.org/ljharb/@wemnyelezxnpm/hic-non-exercitationem/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@wemnyelezxnpm/hic-non-exercitationem#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@wemnyelezxnpm/hic-non-exercitationem.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@wemnyelezxnpm/hic-non-exercitationem.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@wemnyelezxnpm/hic-non-exercitationem.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@wemnyelezxnpm/hic-non-exercitationem
[codecov-image]: https://codecov.io/gh/ljharb/@wemnyelezxnpm/hic-non-exercitationem/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@wemnyelezxnpm/hic-non-exercitationem/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@wemnyelezxnpm/hic-non-exercitationem
[actions-url]: https://github.com/wemnyelezxnpm/hic-non-exercitationem/actions
