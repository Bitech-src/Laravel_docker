# 開発環境構築

## 0. 環境構築に必要なツール

- Docker Desktop がインストールされている事が必要です。
- 作業はコマンドラインから行います。

## 1.各種コンテナの起動

以下を実行します。
```
docker compose up -d
```

## 2. Laravelインストール

以下を実行します。（対象バージョンを指定ください）
```
docker compose exec php composer create-project --prefer-dist laravel/laravel src "9.*"
```
