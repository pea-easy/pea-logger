
[![npm package](https://badge.fury.io/js/pea-logger.svg)](https://www.npmjs.com/package/pea-logger)


# Features
Pea-logger is a further package and extension based on log4js. It supports log for different types of error classification and integration. You can quickly and clearly check the log of current day and many days ago. You can also choose to view only error type of log. 

## Isn't it good? Let's start using it

# Quick Start
## Install
```shell
$ npm i pea-logger
```

## Basic Usage

```javascript

const peaLogger = require('pea-logger');

//Configuration
peaLogger.connect({ name: 'test', level: 'debug' });
// debug
logger.debug(JSON.stringify(process.env));
// info
logger.info('test success');
// error
logger.error('it is wrong');


```

If you want to do some configration of logger, such as error log path, logger name, ...etc 

For example:

```javascript

const config = {
    // this is the name of logger file, default is logger(it contains error logger file name and whole logger file name)
    name: 'test',
    // Configure the log output level
    level: 'debug'
}
peaLogger.connect(config);

```


# Join in!

I'm happy to receive bug reports, fixes, documentation enhancements, and any other improvements.

And since I'm not a native English speaker, if you find any grammar mistakes in the documentation, please also let me know. :)

# Contributors
<table><tr><td width="20%"><a href="https://github.com/TimLiu1"><img src="https://avatars2.githubusercontent.com/u/16770736?s=460&v=4" /></a><p align="center">TimLiu1</p></td><td width="20%"><a href="https://github.com/InCodingNowLiu"><img src="https://avatars0.githubusercontent.com/u/31758568?s=460&v=4" /></a><p align="center">InCodingNowLiu</p></td></tr></table>

# License

MIT