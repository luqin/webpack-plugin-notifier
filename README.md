# webpack-plugin-notifier

webpack plugin that show build status with system notifications

## Installation

```sh
npm install --save-dev webpack-plugin-notifier
```

## Usage

var WebpackNotifierPlugin = require('webpack-plugin-notifier');

// ...
  module: {
    plugins: [
      new WebpackNotifierPlugin(),
    ]
  },
// ...