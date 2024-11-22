# よくあるエラーとその対処法

## コミットまでは進んだけどプッシュでエラーになる

### ユーザー情報が未登録になっている

[レポジトリの登録](https://github.com/DERaC-Global/tag_japan/tree/main/docs/github/localapp/INITIAL_COMMIT.md)を参考にして `git config user.email` でメールアドレスを設定してください

### SSLが未設定または不適正な設定になっている

[Git操作までの下準備](https://github.com/DERaC-Global/tag_japan/tree/main/docs/github/localapp/INIT.md)を参考にして秘密鍵と公開鍵を適正に設定してください。

### レポジトリが更新されている

[初めてのPushとその後のルーティーン](https://github.com/DERaC-Global/tag_japan/tree/main/docs/github/localapp/ROUTINE.md)を参考にしてプルを行ってからプッシュまでの手順を踏んでください。

### プッシュする権限がない

レポジトリを更新する必要がある役割に就いているのに権限の問題でそれができない場合は、リポジトリの管理者に問い合わせてください。

## ファイル・フォルダの全部または一部の追加でエラーになるか警告が出る

### ファイル・フォルダへのアクセス権限が付与されていない

アクセス権がないファイルやフォルダを追加しようとしたとき、エラーや警告が出る場合があります。警告の場合は、それら以外のファイル・フォルダに対しての操作は実行されていますので、プッシュ等の操作が必要な場合はアクセス権限を確認してください。

## Git 関連コマンド全般でエラーになる

### Git コマンドがインストールされていない

[こちらの記事](https://kinsta.com/jp/knowledgebase/install-git/)等を参考にインストールしてください。

### Git コマンドがインストールされている場所にパスが通っていない

コマンドパスを適切に通してください。