# docker_env

## 環境メモ
この環境はローカルにMysql等のDBをインストールする前提で作成されています。

PHP： Version 8.
HttpServer：nginx


## 利用メモ
この環境に複数のgitのリポジトリを配置する場合`git clone`でローカル環境にダウンロード後、
ターミナルでダウンロードフォルダに移動し
`rm -rf .git`を実行し、ファイルを削除するとgitの管理下から開放されます。
