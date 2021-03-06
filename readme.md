# get-query-param [![Build Status](https://secure.travis-ci.org/johnotander/get-query-param.svg?branch=master)](https://travis-ci.org/johnotander/get-query-param) [![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

Get a particular query param from a url.

## Installation

```bash
npm install --save get-query-param
```

## Usage

```javascript
const getQueryParam = require('get-query-param')

getQueryParam('a', 'https://foo.bar?a=hello')  // => 'hello'
getQueryParam('a', '/full/path?a=hello')       // => 'hello'
getQueryParam('b', 'https://foo.bar?a=hello')  // => undefined
getQueryParam('b', 'https://foo.bar')          // => undefined
```

## License

MIT

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Crafted with <3 by John Otander ([@4lpine](https://twitter.com/4lpine)).

***

> This package was initially generated with [yeoman](http://yeoman.io) and the [p generator](https://github.com/johnotander/generator-p.git).
