# rcb

[Ramda](https://github.com/ramda/ramda) [Cookbook](https://github.com/ramda/ramda/wiki/Cookbook) implementation.

## Installation

```
npm install rcb
```

## Usage

```javascript
var R = require('rcb');
```

## API

```javascript
// applyTo :: ({k: v} -> a) -> {k: v} -> a
R.applyTo(fn, obj);

// assign :: String -> a -> {k: v} -> {k: v}
R.assign(prop, val, obj);

// defaults :: {k: v} -> {k: v} -> {k: v}
R.defaults(a, b);

// indexBy :: String -> [{k: v}] -> {String: {k: v}}
R.indexBy(prop, list);

// isArray :: * -> Boolean
R.isArray(value);

// isBoolean :: * -> Boolean
R.isBoolean(value);

// isFunction :: * -> Boolean
R.isFunction(value);

// isNumber :: * -> Boolean
R.isNumber(value);

// isObject :: * -> Boolean
R.isObject(value);

// isPlainObject :: * -> Boolean
R.isPlainObject(value);

// isString :: * -> Boolean
R.isString(value);

// isUndefned :: * -> Boolean
R.isUndefned(value);

// list :: a... -> [a...]
R.list();

// listN :: Number -> a... -> [a...]
R.listN(n);

// mapKeys :: (String -> String) -> {k: v} -> {k: v}
R.mapKeys(fn, obj);

// methodNames :: Object -> [String]
R.methodNames(obj);

// objFromKeys :: (String -> a) -> [String] -> {Strng: a}
R.objFromKeys(fn, keys);

// objSize :: Object -> Number
R.objSize(obj);

// pickIndexes :: [Number] -> [a] -> [a]
R.pickIndexes(indexes, list);

// sliceFrom :: Number -> [a] -> [a]
R.sliceFrom(index, list);

// sliceTo :: Number -> [a] -> [a]
R.sliceTo(index, list);

// toBoolean :: * -> Boolean
R.toBoolean(obj);

// toDate :: * -> Date
R.toDate(obj);

// toNumber :: * -> Number
R.toNumber(obj);

// toString :: * -> String
R.toString(obj);
```

## License

MIT
