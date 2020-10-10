# echo_login

* goのechoを使ってログイン機能付きのtodoアプリを作ってみる！



## ルーティング

| ルート                   | メソッド | 説明               |
| ------------------------ | -------- | ------------------ |
| /                        | GET      | トップ             |
| /signup                  | GET      | 登録画面           |
| /login                   | GET      | ログイン画面       |
| /todos                   | GET      | todo一覧           |
| /signup                  | POST     | 登録処理           |
| /login                   | POST     | ログイン処理       |
| /api/todos               | GET      | ユーザーのtodo取得 |
| /api/todos               | POST     | todo作成           |
| /api/todos/:id           | DELETE   | idのtodoの削除     |
| /api/todos/:id/completed | PUT      | idのtodoの完了     |

