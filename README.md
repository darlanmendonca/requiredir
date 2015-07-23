# About

This module require all files from a directory (only .json, .js, and .coffee), inside a path you want, and return a object with this modules.


# Usage
First install
```sh
npm i --save req-dir
```

And in your files, use:
var reqDir = require('req-dir');
var path = '.'; // path to dir, in this case, same directory
var controllers = reqDir(path);

## Other examples:

var controllers = reqDir('./controllers');
var controllers = reqDir('../controllers');


## Important
The path is relative to parent (file who call) of reqDir.

### Tests
I use mocha for testes, first install mocha has global

```sh
npm i -g mocha
```

Then run tests with:

```sh
npm test
```

Enjoy!
