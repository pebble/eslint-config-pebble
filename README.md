# eslint shareable config for pebble
[![travis][travis-image]][travis-url]
[![npm][npm-image]][npm-url]

[travis-image]: https://img.shields.io/travis/pebble/eslint-config-pebble.svg?style=flat
[travis-url]: https://travis-ci.org/pebble/eslint-config-pebble
[npm-image]: https://img.shields.io/npm/v/eslint-config-pebble.svg?style=flat
[npm-url]: https://npmjs.org/package/eslint-config-pebble

#### An [ESLint](http://eslint.org/) [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for Pebble.

## Install

```bash
npm install eslint-config-pebble
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the shareable config, first run this:

```bash
npm install eslint-config-pebble
```

Then, add this to your .eslintrc file:

```
{
  "extends": "pebble"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.

## License

[MIT](https://github.com/pebble/eslint-config-pebble/blob/master/LICENSE)
