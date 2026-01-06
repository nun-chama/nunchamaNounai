# nunchamaNounai

AI音楽関連の記事を自動収集するリポジトリ

## 機能

- GitHub Actionsを使用して **Google News** と **note** から「AI音楽」に関する記事を自動取得
- 毎日日本時間10:00に実行（手動実行も可能）
- 取得した記事はMarkdown形式で`articles/`フォルダに保存

## ディレクトリ構造

```
articles/
└── YYYY-MM-DD_HHMMSS/
    ├── article_01.md
    ├── article_02.md
    └── ...
```

## 手動実行

GitHub Actions → "Fetch AI Music Articles from X" → "Run workflow" から手動実行できます。
