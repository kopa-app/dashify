# dashify [![NPM version](https://badge.fury.io/js/dashify.svg)](http://badge.fury.io/js/dashify)

> Convert a camelcase or space-separated string to a dash-separated string.

I'm using this for converting object keys to dash-case. Most slugify libs are too heavy for this, so I made this as a fast and light alternative. 

## Install with [npm](npmjs.org)

```bash
npm i dashify --save
```

## Usage

```js
var dashify = require('dashify');

dashify('fooBar');
//=> 'foo-bar'
dashify('fooBarBaz');
//=> 'foo-bar-baz'
dashify('foo bar');
//=> 'foo-bar'
dashify('foo barBaz');
//=> 'foo-bar-baz'
dashify('foo barBaz quux');
//=> 'foo-bar-baz-quux'
```

## Run tests

Install dev dependencies:

```bash
npm i -d && npm test
```

## Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/dashify/issues)

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2015 Jon Schlinkert  
Released under the MIT license

***

_This file was generated by [verb](https://github.com/assemble/verb) on February 12, 2015._