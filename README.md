# [Moment Timezone](http://momentjs.com/timezone)

[![Join the chat at https://gitter.im/moment/moment-timezone](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/moment/moment-timezone?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FEZO801%2Fmoment-timezone.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FEZO801%2Fmoment-timezone?ref=badge_shield)

[![NPM version][npm-version-image]][npm-url] [![NPM downloads][npm-downloads-image]][npm-url] [![MIT License][license-image]][license-url] [![Build Status][travis-image]][travis-url]

IANA Time Zone Database + [Moment.js](http://momentjs.com).

```js
var june = moment("2014-06-01T12:00:00Z");
june.tz('America/Los_Angeles').format('ha z'); // 5am PDT
june.tz('America/New_York').format('ha z');    // 8am EDT
june.tz('Asia/Tokyo').format('ha z');          // 9pm JST
june.tz('Australia/Sydney').format('ha z');    // 10pm EST

var dec = moment("2014-12-01T12:00:00Z");
dec.tz('America/Los_Angeles').format('ha z');  // 4am PST
dec.tz('America/New_York').format('ha z');     // 7am EST
dec.tz('Asia/Tokyo').format('ha z');           // 9pm JST
dec.tz('Australia/Sydney').format('ha z');     // 11pm EST
```

#### [Contribute code or compile time zone data](contributing.md)

#### [Read the changelog](changelog.md)


[license-image]: http://img.shields.io/badge/license-MIT-blue.svg?style=flat
[license-url]: LICENSE

[npm-url]: https://npmjs.org/package/moment-timezone
[npm-version-image]: http://img.shields.io/npm/v/moment-timezone.svg?style=flat
[npm-downloads-image]: http://img.shields.io/npm/dm/moment-timezone.svg?style=flat

[travis-url]: http://travis-ci.org/moment/moment-timezone
[travis-image]: http://img.shields.io/travis/moment/moment-timezone/develop.svg?style=flat


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FEZO801%2Fmoment-timezone.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FEZO801%2Fmoment-timezone?ref=badge_large)