# module-starter [![Build Status](https://travis-ci.org/noamokman/module-starter.svg?branch=master)](https://travis-ci.org/noamokman/module-starter) [![Coverage Status](https://coveralls.io/repos/github/noamokman/module-starter/badge.svg?branch=master)](https://coveralls.io/github/noamokman/module-starter?branch=master)
a cli tool to help you start a new node module

## Installation
As cli tool
```bash
$ [sudo] npm install module-starter -g
```

Programmatically
```bash
$ [sudo] npm install module-starter
```

## Usage
### CLI
```bash
$ module-starter 0.0.0 - a cli tool to help you start a new node module

  USAGE

    module-starter add <a> <b>

  ARGUMENTS

    <a>      The first number       required
    <b>      The second number      required

  GLOBAL OPTIONS

    -h, --help         Display help
    -V, --version      Display version
    --no-color         Disable colors
    --quiet            Quiet mode - only displays warn and error messages
    -v, --verbose      Verbose mode - will also output debug messages
```

### Programmatically
```js
import {add} from 'module-starter';

add(1, 2); // 3
```

## License

[MIT](LICENSE) © [Noam Okman](https://github.com/noamokman)