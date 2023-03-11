# MySQL

## 概要
DockerでMySQLを立ち上げるための設定

## 設定ファイル
|フィールド名|設定|
| :--- | :--- |
| MYSQL_ROOT_PASSWORD | rootユーザーのパスワード |
| MYSQL_USER | 新規ユーザーのユーザー名 |
| MYSQL_PASSWORD | 新規ユーザーのパスワード |
| TZ | タイムゾーン |
| PORT | ホスト側のポート |

## 実行
```bash
$ docker-compose up -d
```

## 停止
```bash
$ docker-compose down
```