# Github-Branch-PR-test

Github でのチーム開発を試すレポジトリです。issue,ブランチ分け,Pull Request を試してみてください。

## 1. issue を作成する

こちらの記事を参考に、新しく issue を作成し、自分自身を割り当ててください。

- Issue に担当者を割り振る  
  までやってもらえば OK です。

https://tonari-it.com/github-issue/

## 2.1. ブランチを分けて作業する

main ブランチから、新しいブランチを作成し、以下の作業を行ってください。

- common.txt を適当に編集
- [github ユーザー名].txt を新しく作成し適当な文章を入力
- [github ユーザー名]\_secret.txt を新しく作成し適当な文章を入力　（API キーなど、機密情報が Push されないようにするための練習）
- .gitignore 　を新しく作成し、　[github ユーザー名]\_secret.txt を記入
  Source Tree, VSCode どちらでも OK ですが、個人的には変更した箇所が分かりやすいので VSCode がおすすめです。
  
2.2 内のリンクを参考にやってみてください。

## 2.2. pull request(PR)を送る

ブランチを作成して、push したら github 上で pull request が作成できます。
Assignees で特定のユーザーに修正を依頼することもできます。
close #X (issue 番号)のようにして、どの issue に対する PR なのかわかるようにしてください。

Source Tree  
https://yumyumtips.net/tool/sourcetree/  
VSCode (どんなやり方でも OK です)  
https://level69.net/archives/26310

## 4. 他の人の pull request をレビューする

ここまで作業が終わったら、別の人の pull request をチェックしてください。  
問題があれば、修正を依頼して、なければ Approve します。  
https://tonari-it.com/github-pull-request-review/

## 5. レビューが承認されたら、マージして、issue を close する。

Approve されていたら、PR を送った人がマージしてください。  
そして、issue が閉じられていなかったら、PR に対応する issue を閉じてください。  
https://tonari-it.com/github-issue-close/

## 変更のたびに必要な作業なので、全員できることを確認してください。
