# stylelint-config-factorial

> Factorial shareable config for stylelint.

Configuration rules to ensure your CSS code is compliant with Factorial's CSS code style. Based on the wonderful work at [SUIT CSS's code style](https://github.com/suitcss/suit/blob/master/doc/STYLE.md).

## Installation

```console
$ npm install stylelint-config-factorial
```

## Usage

Set your stylelint config to:

```json
{
  "extends": "stylelint-config-factorial"
}
```

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
