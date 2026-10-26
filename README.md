## usage

### ローカルでプレビュー

```bash
make up
```

http://localhost:1313/Hugotest/ を開く。

### 記事を書く

`docs/content/posts/` に Markdown を置く（先頭に `title` / `date` の front matter が必要）。
`draft: true` の記事は公開されない。

### 公開

`main` に push すると GitHub Actions（`.github/workflows/hugo.yaml`）がビルドして GitHub Pages に公開する。
