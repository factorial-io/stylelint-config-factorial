**DEPRECATED**: Please use [stylelint-config-suitcss](https://github.com/suitcss/stylelint-config-suitcss) instead.

---

# stylelint-config-factorial

> Factorial shareable config for stylelint.

Configuration rules to ensure your CSS code is compliant with Factorial's CSS code style.

Our configuration extends [stylelint-config-suitcss](https://github.com/suitcss/stylelint-config-suitcss) and is also based on the wonderful work at [SUIT CSS's code style](https://github.com/suitcss/suit/blob/master/doc/STYLE.md).

## Installation

```console
$ npm install stylelint-config-factorial --save-dev
```

## Usage

Create a `.stylelintrc` file in your project and set your config to:

```json
{
  "extends": "stylelint-config-factorial"
}
```

This configuration then can be consumed by [various tools](http://stylelint.io/#quick-start).
We recommend using a [plugin for your build tool and editor](http://stylelint.io/user-guide/complementary-tools/#build-tool-plugins).

### Extending the config

Simply add a `"rules"` key to your config and add your overrides there.

For example, to change the `indentation` to tabs and turn off the `number-leading-zero` rule:


```json
{
  "extends": "stylelint-config-factorial",
  "rules": {
    "indentation": "tab",
    "number-leading-zero": null
  }
}
```

## [Changelog](CHANGELOG.md)

## [License](LICENSE)
