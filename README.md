# Github-Branch-PR-test
Githubでのチーム開発を試すレポジトリです。issue,ブランチ分け,Pull Requestを試してみてください。  
## 1. issueを作成する  
こちらの記事を参考に、新しくissueを作成し、自分自身を割り当ててください。  
- Issueに担当者を割り振る  
までやってもらえばOKです。

https://tonari-it.com/github-issue/  
## 2. ブランチを分けて作業する  
mainブランチから、新しいブランチを作成し、以下の作業を行ってください。  
- common.txt を適当に編集  
- [githubユーザー名].txt を新しく作成し適当な文章を入力  
- [githubユーザー名]_secret.txt を新しく作成し適当な文章を入力　（APIキーなど、機密情報がPushされないようにするための練習）  
- .gitignore　を新しく作成し、　[githubユーザー名]_secret.txtを記入
Source Tree, VSCodeどちらでもOKですが、個人的には変更した箇所が分かりやすいのでVSCodeがおすすめです。
## 3. pull request(PR)を送る
ブランチを作成して、pushしたらgithub上でpull requestが作成できます。
Assigneesで特定のユーザーに修正を依頼することもできます。
close #X (issue番号)のようにして、どのissueに対するPRなのかわかるようにしてください。

Source Tree
https://yumyumtips.net/tool/sourcetree/
VSCode (どんなやり方でもOKです)
https://level69.net/archives/26310
## 4. 他の人のpull requestをレビューする
ここまで作業が終わったら、別の人のpull requestをチェックしてください。
問題があれば、修正を依頼して、なければApproveします。
https://tonari-it.com/github-pull-request-review/
## 5. レビューが承認されたら、マージして、issueをcloseする。
Approveされていたら、PRを送った人がマージしてください。
そして、issueが閉じられていなかったら、PRに対応するissueを閉じてください。
https://tonari-it.com/github-issue-close/

## 変更のたびに必要な作業なので、全員できることを確認してください。
