# do-nothing-loader

A [webpack](http://webpack.github.io/) loader that just returns the module doing nothing to it.

## Install

`npm install --save-dev do-nothing-loader`

## Usage

```javascript
// webpack.config.js

module.exports = {
  ...
  module: {
    loaders: [
      {
        test: /\.js$/,
        loader: 'do-nothing'
      }
    ]
  }
};
```
