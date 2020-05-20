## PJS - Pretty JSON

A simple CLI tool to take json and output it formatted or minified, this depends
entirely on `serde_json`.

## Usage

`pjs` will read from `stdin` and output to `stdout` by default. This can be
adjusted with the `-f` and `-o` flags respectively.

By default the tool will output formatted json, using the `-m` switch will
output a formatting whitespace removed version.

## License

This is licensed under the MIT license.

