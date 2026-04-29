# Sea Breeze Nails

夏向けネイルサロンメニューと予約リクエスト用の静的サイトです。

## 公開ファイル

- `index.html`

## 予約機能

このサイトは静的サイトなので、予約をサーバーに保存しません。お客さまがフォームで予約文面を作成し、次の方法でサロンへ送れるようにしています。

- コピーしてLINEやDMへ貼り付け
- スマホの共有機能で送信
- LINE共有
- メール作成

サロンからの返信をもって予約確定、という運用にしています。

## 受付メールを設定する場合

`index.html` 下部の `salon.email` を変更してください。

```js
email: "reserve@example.com",
```

メール未設定のままでも、コピー、共有、LINE共有は使えます。

## GitHub Pages

`.github/workflows/pages.yml` を含めてGitHubへアップロードすると、GitHub ActionsからPagesへ公開できます。

公開URLの目安:

```text
https://sh21-netizen.github.io/sh21-sea-breeze-nails/
```
