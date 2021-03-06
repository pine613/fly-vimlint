<div align="center">
  <a href="http://github.com/flyjs/fly">
    <img width=200px  src="https://cloud.githubusercontent.com/assets/8317250/8733685/0be81080-2c40-11e5-98d2-c634f076ccd7.png">
  </a>
</div>

> [vimlint](https://github.com/syngan/vim-vimlint) plugin for _[Fly][fly]_.

[![][fly-badge]][fly]
[![npm package][npm-ver-link]][npm-pkg-link]
[![][travis-badge]][travis-link]
[![][climate-badge]][climate-link]
[![][david-badge]][david-link]
[![][david-dev-badge]][david-dev-link]


## Getting Started
This plugin requires [fly](https://github.com/bucaran/fly) and Vim.

```sh
$ npm i fly-vimlint -D
```

## Usage examples

```js
module.exports = function* () {
  yield this.source('./**/*.vim').vimlint()
}
```

## Additional Notes
This plugin **doesn't work** on Windows. It works on Linux, Mac OS X, or other *nix OSs.

## Acknowledgement
This plugin uses following software to validate `.vim` files. Thank you.

 - [syngan](https://github.com/syngan) / [vim-vimlint](https://github.com/syngan/vim-vimlint)
 - [ynkdir](https://github.com/ynkdir) / [vim-vimlparser](https://github.com/ynkdir/vim-vimlparser)

## See also

 -  [node-vimlint](https://github.com/pine/node-vimlint)
 -  [grunt-vimlint](https://github.com/pine/grunt-vimlint)
 -  [gulp-vimlint](https://github.com/pine/gulp-vimlint)

## License
MIT License

[mit]:             http://opensource.org/licenses/MIT
[author]:          https://github.com/pine
[fly]:             https://www.github.com/flyjs/fly
[fly-badge]:       https://img.shields.io/badge/fly-JS-05B3E1.svg?style=flat-square
[mit-badge]:       https://img.shields.io/badge/license-MIT-444444.svg?style=flat-square
[npm-pkg-link]:    https://www.npmjs.org/package/fly-vimlint
[npm-ver-link]:    https://img.shields.io/npm/v/fly-vimlint.svg?style=flat-square
[travis-link]:     https://travis-ci.org/pine/fly-vimlint
[travis-badge]:    http://img.shields.io/travis/pine/fly-vimlint.svg?style=flat-square
[david-link]:      https://david-dm.org/pine/fly-vimlint
[david-badge]:     https://img.shields.io/david/pine/fly-vimlint.svg?style=flat-square
[david-dev-link]:  https://david-dm.org/pine/fly-vimlint#info=devDependencies&view=table
[david-dev-badge]: https://img.shields.io/david/dev/pine/fly-vimlint.svg?style=flat-square
[climate-link]:    https://codeclimate.com/github/pine/fly-vimlint
[climate-badge]:   https://img.shields.io/codeclimate/github/pine/fly-vimlint.svg?style=flat-square
