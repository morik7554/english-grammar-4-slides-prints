# 中学校英語 文法プリント一覧

中学校英語の文法プリントを学年別にまとめた、生徒共有用の静的HTMLサイトです。

Vercelでは `index.html` がトップページとして表示されます。トップページから中1・中2・中3の一覧へ進み、各文法プリントを開けます。

## 入口

- 生徒共有用トップページ：`index.html`
- 3学年まとめページの元ファイル：`all-grades-grammar-index.html`
- 教師用の作成AI画面：`print-generator.html`

## ローカル確認

```bash
python3 -m http.server 5199
```

ブラウザで以下を開きます。

```text
http://127.0.0.1:5199/
```

## Vercel公開

Vercelではビルド不要の静的サイトとして公開します。

- Framework Preset：`Other`
- Build Command：空欄
- Output Directory：`.` または空欄

GitHub連携でデプロイすると、今後このフォルダの変更をpushするだけでVercelへ反映できます。
