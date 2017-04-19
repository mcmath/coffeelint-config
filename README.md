# @mcmath/coffeelint-config

[![Version][version-badge]][npm]
[![Build][build-badge]][travis]

[CoffeeLint][coffeelint] config for [CoffeeScript][coffeescript]
projects

## Install

Install through [npm][npm] as a development dependency.
[CoffeeScript][coffeescript] and [CoffeeLint][coffeelint] should also be
installed.

```sh
npm install --save-dev coffee-script coffeelint @mcmath/coffeelint-config
```

## Usage

Create a `coffeelint.json` file at the root of your project with the following
contents:

```json
{ "extends": "@mcmath/coffeelint-config" }
```

Rules may be added or modified like so:

```json
{
  "extends": "@mcmath/coffeelint-config",
  "indentation": {
    "level": "error",
    "value": 2
  },
  "max_line_length": {
    "level": "ignore"
  }
}
```

[version-badge]: https://img.shields.io/npm/v/@mcmath/coffeelint-config.svg?style=flat-square
[build-badge]: https://img.shields.io/travis/mcmath/coffeelint-config/master.svg?style=flat-square
[npm]: https://www.npmjs.com/package/@mcmath/coffeelint-config
[travis]: https://travis-ci.org/mcmath/coffeelint-config
[coffeescript]: http://coffeescript.org/
[coffeelint]: http://www.coffeelint.org/
