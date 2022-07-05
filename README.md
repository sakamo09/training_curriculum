
heroku open
⇨ヘロクのアプリをブラウザに表示させるコマンド

git push heroku master
⇨ヘロクに変更を反映するコマンド

heroku run DISABLE_DATABASE_ENVIRONMENT_CHECK=1 rails db:drop db:create db:migrate
⇨ヘロクのデータベースをリセットするコマンド