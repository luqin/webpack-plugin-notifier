# webpack-plugin-notifier

[![NPM version][npm-badge]][npm]

[npm-badge]: http://badge.fury.io/js/webpack-plugin-notifier.svg
[npm]: http://badge.fury.io/js/webpack-plugin-notifier

webpack plugin that show build status with system notifications

## Installation

```sh
npm install --save-dev webpack-plugin-notifier
```

## Usage

```js
var WebpackNotifierPlugin = require('webpack-plugin-notifier');

// ...
  module: {
    plugins: [
      new WebpackNotifierPlugin(),
    ]
  },
// ...
```