# README

格納されているソースコードのWebアプリ起動手順を以下に記載致します。

ターミナルを開いてカレントワーキングディレクトリを、ディレクトリをクローンしたい場所に変更し、以下のコマンドでgit cloneを実行

$ git clone https://github.com/yuta-yamaura/rails-docker.git

rails db:create コマンドを実行します。これにより、データベースが作成されます。

$ docker-compose run --rm web rails db:create

docker-composeでコンテナを起動

$ docker-compose up

ブラウザのURLにhttp://localhost:3000を入力し押下

Webアプリが起動されます。

以上
