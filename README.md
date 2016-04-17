# logger


[![Build Status](https://travis-ci.org/plover-modules/logger.svg?branch=master)](https://travis-ci.org/plover-modules/logger)
[![Coverage Status](https://coveralls.io/repos/github/plover-modules/logger/badge.svg?branch=master)](https://coveralls.io/github/plover-modules/logger?branch=master)


【核心模块】提供统一的日志接口，让使用者不用关心日志实现，方便日志实现切换。


```js
const log = require('plover-logger')('MyClass');

log.info('init application: %s', name);
log.error(e);
log.debug('data return: %o', data);
log.warn('data already exist: %o', o);
```
