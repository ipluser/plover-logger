# logger


[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]


【核心模块】提供统一的日志接口，让使用者不用关心日志实现，方便日志实现切换。


```js
const log = require('plover-logger')('MyClass');

log.info('init application: %s', name);
log.error(e);
log.debug('data return: %o', data);
log.warn('data already exist: %o', o);
```


[npm-image]: https://img.shields.io/npm/v/plover-logger.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/plover-logger
[travis-image]: https://img.shields.io/travis/plover-modules/plover-logger/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/plover-modules/plover-logger
[coveralls-image]: https://img.shields.io/codecov/c/github/plover-modules/plover-logger.svg?style=flat-square
[coveralls-url]: https://codecov.io/github/plover-modules/plover-logger?branch=master
