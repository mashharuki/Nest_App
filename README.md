# Nest_App
nest.jsを使ったリポジトリです。

### 起動コマンド
  `npm run start:dev`

### ORMでMySQLなどを使用する場合
    ormconfig.jsonを次の用に記述する。

  <code>
  
  {  
  　"type": "mysql" or "postgres",  
  　"host": "ホスト名",  
  　"port": ポート番号,  
  　"username": "ユーザー名",  
  　"password": "パスワード",  
  　"database": "データベース名"  
  } 
  </code>