# sample-pr-multiple-template

複数のPRテンプレートの使用例

## PRテンプレート格納先

### デフォルト
`/.github/PULL_REQUEST_TEMPLATE.md`

### デフォルト以外
`/.github/PULL_REQUEST_TEMPLATE/*`

## 使い方

URLで指定する。

### クエリ
- `extend=1`
  - これを付けると最初からPR本文の入力画面になる
- `template`
  - テンプレートを指定する。テンプレート名には拡張子も必要。
- `title`
  - PRタイトルを指定する。

```
https://github.com/mygkw/sample-pr-multiple-template/compare/${ブランチ名}?expand=1&template=${テンプレート名}&title=${PRタイトル}
```

### e.g.
https://github.com/mygkw/sample-pr-multiple-template/compare/sample_branch1?expand=1&template=template1.md&title=title_YYYY-MM-DD

### ドキュメント
https://docs.github.com/ja/issues/tracking-your-work-with-issues/creating-issues/about-automation-for-issues-and-pull-requests-with-query-parameters

