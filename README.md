# babel-preset-es2015-node4

> Babel preset to make node@4 ES2015 compatible.

## Install

```sh
$ npm install --save-dev babel-preset-es2015-node4
```

## Usage

### Via `.babelrc` (Recommended)

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
require("babel-core").transform("code", {
  presets: ["es2015-node4"]
});
```