## mocha-fivemat-reporter

Reporter for the [mocha][1] test framework based on Tim Pope's
[fivemat][2].

![Fivemat Output](http://i.imgur.com/mcvLPZF.png?1)

## Installation

Add it to the `devDependencies` in your `package.json` and `npm install`.

```json
{
  "devDependencies": {
    "mocha-fivemat-reporter": "*"
  }
}
```

## Usage

After installation you can use `mocha-fivemat-reporter` as the reporter name with the
`-R` or `--reporter` switch.

    $ mocha -R mocha-fivemat-reporter

With `mocha.opts` this can be done with,

```js
--reporter mocha-fivemat-reporter
```

[1]: https://github.com/visionmedia/mocha
[2]: https://github.com/tpope/fivemat
