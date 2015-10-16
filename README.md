fly-vimlint
------------

[![][fly-badge]][fly]
[![npm package][npm-ver-link]][npm-pkg-link]
[![][travis-badge]][travis-link]
[![][mit-badge]][mit]

Validate `.vimrc`, `.vim` files with [vimlint](https://github.com/syngan/vim-vimlint).

## Getting Started
This plugin requires [fly](https://github.com/bucaran/fly) and Vim.

```sh
$ npm i fly-vimlint -D
```

## Usage examples

```
export default function* () {
  yield this.source('**/*.vim').vimlint()
}
```

## Additional Notes
This plugin **doesn't work** on Windows. It works on Linux, Mac OS X, or other *nix OSs.

## Acknowledgement
This plugin uses following software to validate `.vim` files. Thank you.

 - [syngan](https://github.com/syngan) / [vim-vimlint](https://github.com/syngan/vim-vimlint)
 - [ynkdir](https://github.com/ynkdir) / [vim-vimlparser](https://github.com/ynkdir/vim-vimlparser)

## See also

 -  [node-vimlint](https://github.com/pine613/node-vimlint)
 -  [grunt-vimlint](https://github.com/pine613/grunt-vimlint)
 -  [gulp-vimlint](https://github.com/pine613/gulp-vimlint)

## License
MIT License<br />
Copyright (c) 2015 Pine Mizune

[mit]:          http://opensource.org/licenses/MIT
[author]:       https://github.com/pine613
[contributors]: https://github.com/kashiro/fly-vimlint/graphs/contributors
[fly]:          https://www.github.com/flyjs/fly
[fly-badge]:    https://img.shields.io/badge/fly-JS-05B3E1.svg?style=flat-square
[mit-badge]:    https://img.shields.io/badge/license-MIT-444444.svg?style=flat-square
[npm-pkg-link]: https://www.npmjs.org/package/fly-vimlint
[npm-ver-link]: https://img.shields.io/npm/v/fly-vimlint.svg?style=flat-square
[travis-link]:  https://travis-ci.org/pine613/fly-vimlint
[travis-badge]: http://img.shields.io/travis/pine613/fly-vimlint.svg?style=flat-square