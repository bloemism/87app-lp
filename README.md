# 87app LP

87app 紹介用ランディングページ（GitHub Pages 向け静的サイト）。

- 本番アプリ（店舗登録）: https://87app.vercel.app/
- 構想の元記事: https://note.com/bloemism/n/n37db7ee7c85d

## 構成

```
index.html          # LP 本体
guide.html          # 登録手順ガイド（ユーザー登録〜店舗/スクール）
styles.css          # 共通スタイル
assets/
  hero.png          # ヒーロー
  service-life.png  # サービス全体の流れ
  points.png        # ポイント仕組み
  schedule.png      # スケジュール
  map-*-initial.svg # ガイド用マップ初期イメージ（実データなし）
```

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
