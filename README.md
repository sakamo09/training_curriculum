
heroku open
⇨ヘロクのアプリをブラウザに表示させるコマンド

git push heroku master
⇨ヘロクに変更を反映するコマンド

heroku run DISABLE_DATABASE_ENVIRONMENT_CHECK=1 rails db:drop db:create db:migrate
⇨ヘロクのデータベースをリセットするコマンド




rails g device user(モデル名）
⇨deviceに関するモデルを作成するときに使う
（ルーテｲングとマイグレーションファイルも一緒にできる）
