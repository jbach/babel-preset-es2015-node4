# babel-preset-es2015-node4

> Babel preset to make node@4 ES2015 compatible.

Node@4 has great [ES2015 support](https://nodejs.org/en/docs/es6/),
this module just adds missing features:
- destructing assignment
- rest & default parameters
- modules
- unicode and sticky regular expressions
- spread operator

## Install

```sh
$ npm install --save-dev babel-preset-es2015-node4
```

## Usage

### Via `.babelrc` (recommended)

**.babelrc**

```json
{
  "presets": ["es2015-node4"]
}
```

### Via CLI

```sh
$ babel script.js --preset es2015-node4
```

### Via Node API

```javascript
require('babel-core').transform('code', {
  presets: ['es2015-node4'],
})
```

## License

[MIT](./LICENSE)
