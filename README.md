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



## 改善点

* もう少しjsに頼らず実装したい

  →ルートでhtmlをそのまま返しているところが目立つ

  →改善するとルーティングももう少しきれいになるはず

1. ページを返している箇所を全てgetにして書き直す
2. apiを呼び出している箇所はルートを呼び出すようにする





## 使用技術

go 1.14

jwt

echo

gorm



