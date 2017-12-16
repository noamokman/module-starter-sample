# cli 
cli cli

## Installation
As cli tool
```bash
$ [sudo] npm install cli -g
```

Programmatically
```bash
$ [sudo] npm install cli
```

## Usage
### CLI
```bash
$ cli 0.0.0 - cli cli

  USAGE

    cli add <a> <b>

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
import {add} from 'cli';

add(1, 2); // 3
```

## License

[ISC](LICENSE)