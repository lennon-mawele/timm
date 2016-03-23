# Changelog

## 0.5.1, 0.5.2 (Mar. 23, 2016)

* Distribute 4 versions of Timm:
    - ES5 (default): `timm.js` (just `require('timm')`)
    - ES5 minimised: `timm.min.js`
    - ES6: `timm_es6.js`
    - ES6 with Flow type annotations: `timm_es6_flow.js`

## 0.5.0 (Mar. 23, 2016)

* Important internal changes (migrated to AVA, ES6, Flow), but usage remains unchanged

## 0.4.3 (Mar. 08, 2016)

* Bugfix: internal `_merge()` incorrectly merged `{a: 3} + {a: undefined} => {a: undefined}`

## 0.4.2 (Feb. 28, 2016)

* Update documentation for the new functions added in 0.4.1.

## 0.4.1 (Feb. 28, 2016)

* Add `getIn()`, `updateIn()`, `mergeIn()`
* `setIn()` now creates nested objects for unknown paths
* Bugfix: internal `_clone()` converted arrays to objects

## 0.4.0 (Feb. 25, 2016)

* Accept arrays in array operations `addLast()` and `addFirst()`.
* Add new array operation `insert()`.