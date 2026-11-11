# Arxcs 個人シート

チームで共有して使う見込み顧客・IAA管理アプリです。GitHub Pages で公開し、データは Firebase（無料の Spark プラン）に保存します。

- 画面：`index.html`（1ファイル）
- Firebase の接続設定：`config.js`
- データベースのルール：`firestore.rules`（`SETUP_KEY_HERE` を管理者用の設定キーに置き換えてから、Firebase コンソールに貼り付けます。設定キーはこのリポジトリに書かないでください）

ログインはGoogleアカウントです。「招待リンク → Googleでログイン → 名前を確認して登録」で参加し、以後はGoogleでログインするだけで自分のシートが開きます（一度ログインした端末では自動ログイン）。Firebaseの Authentication で「Google」を有効にし、承認済みドメインに seiya-super.github.io を追加しておく必要があります。招待リンクは管理画面の「招待・アカウント」で作成します。
