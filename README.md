# process
日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A `process` object emulator for Deno / ES modules.

## Features
- Provides a `process` object emulating the Node.js `process` object for Deno
- Includes `argv`, `stderr`, `stdout`, `exit`, `on`, `env`, and `platform` properties
- Allows writing to `stderr` and `stdout` through the provided objects

## Usage
To use the `process` emulator, import the default export from the `process.js` file:

```javascript
import process from './process.js';
```

You can then access the `process` object and its properties and methods.

## License
This project is licensed under the [MIT License](LICENSE).
