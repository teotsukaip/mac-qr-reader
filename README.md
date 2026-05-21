# mac-qr-reader

Mac のブラウザで動作する QR コードリーダーです。フロントカメラで QR コードを読み取り、URL を表示します。リンクをクリックすると別タブで開きます。

## 使い方

1. このリポジトリを Web サーバー（または GitHub Pages）に公開する
2. ブラウザで `index.html` を開く
3. カメラの使用を許可する
4. QR コードを画面中央の枠に合わせる
5. 読み取った URL をクリックして別タブで開く

## 公開（GitHub Pages）

リポジトリの **Settings → Pages** で Source を `main` ブランチに設定すると、次の URL で利用できます。

`https://teotsukaip.github.io/mac-qr-reader/`

## 注意

- カメラ利用には **HTTPS** が必要です（GitHub Pages は HTTPS 対応）
- `file://` で直接開くと、ブラウザによってはカメラが使えません
- QR 読み取りには [jsQR](https://github.com/cozmo/jsQR)（CDN）を使用しています

## ファイル構成

| ファイル | 説明 |
|---------|------|
| `index.html` | QR コードリーダー本体 |
