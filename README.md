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

## License

`stylelint-config-mirego` is © 2018 [Mirego](http://www.mirego.com) and may be freely distributed under the [New BSD license](http://opensource.org/licenses/BSD-3-Clause).
See the [`LICENSE.md`](https://github.com/mirego/stylelint-config-mirego/blob/master/LICENSE.md) file.

## About Mirego

[Mirego](https://www.mirego.com) is a team of passionate people who believe that work is a place where you can innovate and have fun. We're a team of [talented people](https://life.mirego.com) who imagine and build beautiful Web and mobile applications. We come together to share ideas and [change the world](https://www.mirego.org).

We also [love open-source software](https://open.mirego.com) and we try to give back to the community as much as we can.
