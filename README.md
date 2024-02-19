# README

格納されているソースコードのWebアプリ起動手順を以下に記載致します。

ターミナルを開いてカレントワーキングディレクトリを、ディレクトリをクローンしたい場所に変更し、以下のコマンドでgit cloneを実行
$ git clone https://github.com/yuta-yamaura/rails-docker.git

docker-composeでコンテナを起動
$ docker-compose up
※docker-compose upコマンドを実行する度にrails db:createを実行するので、コンテナの起動は１回でお願い致します。

ブラウザのURLにhttp://localhost:3000を入力し押下

Webアプリが起動されます。

以上
