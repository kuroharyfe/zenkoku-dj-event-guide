# 全国DJイベントガイド

静的なイベント検索サイトです。追加のビルド工程や有料サービスは不要です。

## GitHub Pagesへの無料公開

1. GitHubで空の**公開**リポジトリ `zenkoku-dj-event-guide` を作成してください。
2. `index.html` と `.nojekyll` をリポジトリのルートにアップロードしてください。
3. リポジトリの **Settings → Pages** で、公開元を `Deploy from a branch`、ブランチを `main`、フォルダーを `/ (root)` に設定します。
4. 公開後のURLは通常 `https://kuroharyfe.github.io/zenkoku-dj-event-guide/` です。

GitHub FreeではPagesを公開リポジトリで利用します。リポジトリとサイトはインターネット上で誰でも閲覧できます。

## 内容と注意

- `index.html` — サイト本体。イベント情報はデザイン確認用のサンプルです。
- `.nojekyll` — GitHub Pagesに静的ファイルとして配信させる設定ファイル。
- SNS投稿フォームの登録内容は入力したブラウザー内だけに保存され、他の人とは共有されません。SNS投稿本文の自動取得も行いません。
- 現在地検索には訪問者の許可が必要です。公開後の位置情報利用はHTTPSで動作します。
- Google Fontsを読み込むため、フォント表示にはインターネット接続が必要です。

