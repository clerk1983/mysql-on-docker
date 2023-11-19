# MySQL on Docker

## docker-composeでコンテナを起動(./docker-mysqlディレクトリ)

docker compose up -d

## 実行中コンテナにログイン

docker exec -it mysql-container bash

## コンテナイメージ一覧

docker image ls

## 実行中のコンテナ一覧

docker ps
