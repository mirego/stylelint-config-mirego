# stylelint-config-mirego
💅 The shareable stylelint configuration we use at Mirego

## Installation

```
npm i -D stylelint-config-mirego
```

## Usage

If you’ve installed `stylelint-config-mirego` locally within your project, just set your stylelint config to:

```json
{
  "extends": "stylelint-config-mirego"
}
```

## Non-Sass Users

We have one rule that enforces the use of a Sass feature. If you don’t use Sass, you must disable that rule:

```json
{
  "extends": "stylelint-config-mirego",
  "rules": {
    "mirego/prefer-sass-rgba-function": null
  }
}
```
