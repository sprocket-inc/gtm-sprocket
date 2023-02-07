# gtm-sprocket

Sprocket タグ及びSprocket データ連携タグ（リアルタイム取り込み）を Google タグマネージャにインポートするためのコンテナデータです。  
上記タグの導入にご利用ください。

## GTMコンテナにSprocketタグを導入するには

[sprocket.json](./container/sprocket.json)を取得し、GTMコンテナへインポートしてください。  
インポート後、GTMコンテナにて変数等の設定を行ってください。

## GTMコンテナにデータ連携タグを導入するには

導入したいデータ連携タグに対応する設定ファイルを全て取得し、GTMコンテナへインポートしてください。  
データ連携タグに対応する設定ファイルは以下テーブルよりご確認ください。

| データ連携タグ | 設定ファイル |
| --- | --- |
| ユーザー属性タグ | [user-data.json](./container/user-data.json) |
| ログイン状態タグ | [login-status.json](./container/login-status.json) |
| 購入データタグ | [purchase-data.json](./container/purchase-data.json) |
| カート内データタグ | [cart-data.json](./container/cart-data.json) |

例えばユーザー属性タグを導入する場合、[user-data.json](./container/user-data.json)を取得してGTMコンテナへインポートします。  
インポート後、GTMコンテナにて変数等の設定を行ってください。

## 変更履歴

| 日付 | バージョン | 詳細 |
| ------- | ------ | ----- |
| 2023-02-07 | 1.0.1 | README.md を更新 | 
| 2021-05-13 | 1.0.0 | バージョン 1.0.0 をリリース | 
