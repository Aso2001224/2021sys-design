```
@startuml
opt 未登録
ユーザー->webサーバー:ユーザー登録
webサーバー->DBサーバー:ユーザー登録
DBサーバー->DBサーバー:登録処理
DBサーバー->webサーバー:登録結果

alt 登録成功
webサーバー->ユーザー:登録メッセージを表示
else 登録失敗
end

@startuml
opt ログイン
alt ログイン成功
webサーバー->ユーザー: ログイン成功画面表示
else ログイン失敗

end
