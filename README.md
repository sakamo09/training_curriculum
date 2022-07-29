
heroku open
⇨ヘロクのアプリをブラウザに表示させるコマンド

git push heroku master
⇨ヘロクに変更を反映するコマンド

heroku run DISABLE_DATABASE_ENVIRONMENT_CHECK=1 rails db:drop db:create db:migrate
⇨ヘロクのデータベースをリセットするコマンド

heroku config
⇨ヘロクの環境変数一覧が見れるコマンド


rails g model モデル名(単数系）
⇨モデルを作成するコマンド

rails g controller コントローラー名（複数形）
⇨コントローラーを作成するコマンド

rails d ファイルの種類 削除するファイル名
⇨rails gコマンドで生成したファイル一式をすべて削除するコマンド

rails g device user(モデル名）
⇨deviceに関するモデルを作成するときに使う
（ルーテｲングとマイグレーションファイルも一緒にできる）

rails d ファイルの種類 削除するファイル名
⇨コントローラーを消すコマンド


binding.pry
⇨処理を止める

bundle install
⇨Gemを記述したら必ず実行する
