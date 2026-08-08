# 87app LP

87app 紹介用ランディングページ（GitHub Pages 向け静的サイト）。

- 本番アプリ（店舗登録）: https://87app.vercel.app/
- 構想の元記事: https://note.com/bloemism/n/n37db7ee7c85d

## 構成

```
index.html          # LP 本体
assets/
  hero.svg          # ヒーロー（差し替え可 → hero.jpg 等）
  service-flow.svg  # サービス流れ
  service-care.svg  # サービス補足
  cta.svg           # 最終 CTA 背景
```

画像を差し替えるときは `assets/` に実写を置き、`index.html` 内の `src` を対応するファイル名に変更してください。

## ローカル確認

```bash
# 例: Python
python3 -m http.server 8080
# → http://localhost:8080
```

## GitHub Pages の有効化

1. リポジトリ **Settings → Pages**
2. **Build and deployment → Source**: Deploy from a branch
3. **Branch**: `main` / `/ (root)`
4. Save 後、数分で `https://bloemism.github.io/87app-lp/` で公開されます
