# MySQL on Docker

## docker-compose でコンテナを起動(./docker-mysql ディレクトリ)

docker compose up -d

## 実行中コンテナにログイン

docker exec -it mysql-container bash

## MySQL 接続

mysql -uroot -p

## コンテナイメージ一覧

docker image ls

## 実行中のコンテナ一覧

docker ps
