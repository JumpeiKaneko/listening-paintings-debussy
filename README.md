# 絵画を聴く（ドビュッシー4曲と絵）

展示で、絵の横のQRコードから曲を聴くためのサイトです。

## 音源を入れる

`audio/` に次の名前で mp3 を入れます。

- `01-moonlight.mp3`：月の光
- `02-arabesque.mp3`：2つのアラベスク 第1番
- `03-bruyeres.mp3`：ヒースの茂る荒れ地
- `04-la-fille.mp3`：亜麻色の髪の乙女

GitHub は1ファイル100 MBまでです。

## 公開する（GitHub Pages）

1. GitHub で、このフォルダと同じ名前のリポジトリ（`listening-paintings-debussy`）を作る
2. このフォルダの中身をすべて上げる
3. リポジトリの Settings → Pages で、Branch を `main`、フォルダを `/ (root)` にして Save
4. 数分後、`https://jumpeikaneko.github.io/listening-paintings-debussy/` で開ける（キャプションのQRコードはこの住所で作ってあります。リポジトリ名を変えるとQRが使えなくなります）

## QRコードを印刷する

公開したあと、`https://（ユーザー名）.github.io/listening-paintings-debussy/qr.html` を開いて印刷します（A4に4つ）。

## ページ

- `index.html`：はじめのページ（ステートメントと4曲の一覧）
- `01-moonlight/` 〜 `04-la-fille/`：1曲1ページ（絵、音源、キャプション、編曲のコンセプト）
- `qr.html`：QRコード
