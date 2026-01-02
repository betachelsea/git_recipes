# Git・Pull Request 活用プラクティス

コーディングを進めるにあたり、Git・Pull Requestの活用方法を学ぶための練習用リポジトリです。
課題1・2 の回答は、FBCの提出物のページにコメントとして記載してください。
課題3 の回答は、Pull Requestとして作成し、URLを提出してください。

## 課題1: Pull Request の問題点を発見する

https://github.com/fjordllc/git_recipes に用意してある2件のPull Requestについて、問題点を指摘してください。

## 課題2: 履歴の調べ方を確認する

`recipes/nikujyaga.html` 内の「しょうゆ」という表記は、以前は「醤油」と書かれていましたが、とある理由により漢字をひらくように変更されました。この変更が入った理由を、Gitの履歴から確認してください。

## 課題3: 実際によい Pull Request を作る体験をする

「肉じゃが」のレシピに対して、次のような意見が挙がったので、対応することになりました。
このリポジトリをForkして、自身のリポジトリにて下記を解決する Pull Request を作成してください。
(提出方法の参考は[こちら](https://github.com/fjordllc/bug_reversi?tab=readme-ov-file#%E6%8F%90%E5%87%BA%E6%96%B9%E6%B3%95))
今回のcommitの際には、1変更1commitの粒度で対応してください。

- 肉じゃがの写真が大きすぎるので、最大の横幅を 300px になるように制限する
- 「白滝」の表記がわかりにくいので、「しらたき」に変更する
- ポイントの記載sectionに `class="tips"` を適用する

