# snape-config [![Build Status](https://travis-ci.org/ritz078/electron-app-config.svg?branch=master)](https://travis-ci.org/ritz078/electron-app-config)

> A node module to store and read snape's application config.


## Install

```
$ npm install --save snape-config
```


## Usage

```js
const config = require('snape-config');

electronAppConfig('unicorns');
//=> 'unicorns & rainbows'
```


## API

### .readConfig((err, data) => console.log(err, data))
Reads the application config.

### .addToConfig(object, cb)
Merges the `object` with existing config.

### .replace(obj, cb)
Replace the config with `obj`

## License

MIT © [Ritesh Kumar](https://github.com/ritz078/snape-config)
