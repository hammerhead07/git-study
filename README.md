# Gitの勉強

- git add コマンドで、リポジトリに変更情報を追加する。
  - このことをステージングと言う
- git commit コマンドで、リポジトリのインデックスに追加された変更情報にコメントをつけてコミットできる
- git push コマンドで、ローカルのコミットをリモートのリポジトリに反映させることができる

- git push -u origin master
  - -u は次回以降、origin と master を省略したときに自動でこの値とするためのオプション
- git commit -m "コメント" でコメントを残してコミットする
- git status で現在の状態を確認できる。登録（ステージング）状況を確認できる。
- git log でコミットログを確認できる。
- git remote add origin リモートリポジトリ でリモートリポジトリのoriginの場所を指定する
- git tag タグ名 でタグを作成する。
- git push --tags origin master でタグをpush
