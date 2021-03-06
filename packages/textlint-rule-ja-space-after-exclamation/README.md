# textlint-rule-ja-space-after-exclamation

感嘆符前後のスペースについてのtexlintルール

文末に感嘆符を使用し、後に別の文が続く場合は、直後に全角スペースを挿入します。
文中に感嘆符を使用する場合はスペースを挿入しません

    OK: 驚きの速さ！　これが新製品のキャッチコピーでした。
    NG: 驚きの速さ！ これが新製品のキャッチコピーでした。

## Install

Install with [npm](https://www.npmjs.com/):

    npm install textlint-rule-ja-space-after-exclamation

## Usage

Via `.textlintrc`(Recommended)

```json
{
    "rules": {
        "ja-space-after-exclamation": true
    }
}
```

Via CLI

```
textlint --rule ja-space-after-exclamation README.md
```

## Fixable

[![textlint rule](https://img.shields.io/badge/textlint-fixable-green.svg?style=social)](https://textlint.github.io/)

`textlint --fix`の自動修正に対応しています。

## Changelog

See [Releases page](https://github.com/extlint-ja/textlint-rule-spacing/releases).

## Running tests

Install devDependencies and Run `npm test`:

    npm i -d && npm test

## Contributing

Pull requests and stars are always welcome.

For bugs and feature requests, [please create an issue](https://github.com/extlint-ja/textlint-rule-spacing/issues).

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Author

- [github/azu](https://github.com/azu)
- [twitter/azu_re](https://twitter.com/azu_re)

## License

MIT © azu
