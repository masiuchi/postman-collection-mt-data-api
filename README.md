# Postman collection file for Movable Type Data API

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/87eaa964fa09e5de35ee#?env%5BMT%20Data%20API%20sample%20environment%5D=W3siZW5hYmxlZCI6dHJ1ZSwia2V5IjoidXJsIiwidmFsdWUiOiJodHRwOi8vbG9jYWxob3N0L210L210LWRhdGEtYXBpLmNnaSIsInR5cGUiOiJ0ZXh0In0seyJlbmFibGVkIjp0cnVlLCJrZXkiOiJ2ZXJzaW9uIiwidmFsdWUiOiJ2MyIsInR5cGUiOiJ0ZXh0In0seyJlbmFibGVkIjp0cnVlLCJrZXkiOiJjbGllbnRJZCIsInZhbHVlIjoicG9zdG1hbiIsInR5cGUiOiJ0ZXh0In0seyJlbmFibGVkIjp0cnVlLCJrZXkiOiJ1c2VybmFtZSIsInZhbHVlIjoiYWRtaW4iLCJ0eXBlIjoidGV4dCJ9LHsiZW5hYmxlZCI6dHJ1ZSwia2V5IjoicGFzc3dvcmQiLCJ2YWx1ZSI6InBhc3N3b3JkIiwidHlwZSI6InRleHQifV0=)

## 概要

* Movable Type Data API v3.1 時点でのエンドポイントを Postman の collection にしました。
* API URL、ログイン情報、URL パラメータは environment に保存して使います。
* セッション ID・アクセストークンは Auth 系のエンドポイントをリクエストした後に environment で自動的に更新されます。
* 認証が必要なエンドポイントは envrionment にあるアクセストークンを自動的に使用します。

## 使い方

### collection と environment のインポート
* 上の「Run in Postman」ボタンをクリックして、collection と environment を Postman にインポートする。
  * Postman for Chrome を使っている場合は、Chrome で上記ボタンをクリックする必要がありそうです。
  
![](https://github.com/masiuchi/postman-collection-mt-data-api/blob/master/open_postman.png?raw=true)

### environment の設定
* url(API URL), username, password を適切に設定してください。
* site_id, entry_id などの URL パラメータもここで指定してください。

![](https://github.com/masiuchi/postman-collection-mt-data-api/blob/master/postman.png?raw=true)
![](https://github.com/masiuchi/postman-collection-mt-data-api/blob/master/environment_list.png?raw=true)
![](https://github.com/masiuchi/postman-collection-mt-data-api/blob/master/edit_environment.png?raw=true)
