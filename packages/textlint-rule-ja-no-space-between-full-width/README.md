# textlint-rule-ja-no-space-between-full-width

全角文字同士の間のスペースについてのtextlintルール

全角文字どうしの間にスペースを入れません。
ただしカタカナ複合語の場合を除きます。

    OK: これは大丈夫。
    NG: これは ダメ

## Install

Install with [npm](https://www.npmjs.com/):

    npm install textlint-rule-ja-no-space-between-full-width

## Usage

Via `.textlintrc`(Recommended)

```json
{
    "rules": {
        "ja-no-space-between-full-width": true
    }
}
```

Via CLI

```
textlint --rule ja-no-space-between-full-width README.md
```

## Fixable

[![textlint rule](https://img.shields.io/badge/textlint-fixable-green.svg?style=social)](https://textlint.github.io/)

`textlint --fix`の自動修正に対応しています。

## Changelog

See [Releases page](https://github.com/textlint-ja/textlint-rule-spacing/releases).

## Running tests

Install devDependencies and Run `npm test`:

    npm i -d && npm test

## Contributing

Pull requests and stars are always welcome.

For bugs and feature requests, [please create an issue](https://github.com/textlint-ja/textlint-rule-spacing/issues).

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
