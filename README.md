# @mcmath/coffeelint-config

[CoffeeLint][coffeelint] configuration for [CoffeeScript][coffeescript]
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

[npm]: https://www.npmjs.com/package/@mcmath/coffeelint-config
[coffeescript]: http://coffeescript.org/
[coffeelint]: http://www.coffeelint.org/
