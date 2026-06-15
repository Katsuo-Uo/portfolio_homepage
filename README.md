# イルマタルのプログラミング学習予定帳 - 紹介サイト

神話をモチーフにした4人のキャラクターと、Androidアプリ
「イルマタルのプログラミング学習予定帳」のポートフォリオサイトです。

## 確認方法

`index.html` をブラウザで開くと確認できます。

ローカルサーバーを使う場合:

```bash
npx serve .
```

## 公開

静的サイトのため、GitHub Pages、Netlify、Cloudflare Pagesなどへそのまま配置できます。

## APKの配布

Androidアプリの配布には、リポジトリへ直接APKを置く方法ではなく、
GitHub Releasesの利用を推奨します。公開版は専用のリリースキーで署名し、
バージョン、対応Android、変更内容、ファイルサイズ、SHA-256チェックサムを
Release Notesへ記載してください。

## ライセンス

- HTML、CSS、JavaScriptなどのソースコード: [MIT License](./LICENSE)
- キャラクター画像、アイコン、スプライト、APK:
  [個別の利用条件](./ASSETS_LICENSE.md)
- Google Fonts: 各フォントの提供元ライセンスに従います

コードのライセンスは、画像やアプリ本体の利用許諾を含みません。
キャラクター画像は生成AIを利用し、制作者による企画、指示、選択および
編集を経て制作されています。

## ファイル構成

```text
index.html
app.html
home.css
home.js
styles.css
script.js
LICENSE
ASSETS_LICENSE.md
assets/
```
