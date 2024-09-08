# git操作をVSCodeで行う

## clone
![git-vscode-clone](./images/git-vscode-clone.png)

VScodeの左のメニューから、`Source Control`を選択し、`Clone Repository`を選択します。
リポジトリのURL(ssh)を入力し、保存先を選択します。

## ブランチの切り替え
![git-vscode-branch](./images/git-vscode-branch.png)

VScodeの左下にブランチ名（はじめはmain）が表示されています。
クリックすると、切り替えることができます。
作成もここから行うことができます。

## コミット
![git-vscode-add](./images/git-vscode-add.png)

`Source Control`から、`+`をクリックし、コミットしたいファイルをステージに上げます。
ステージとは、コミットするファイルを選択することです。

![git-vscode-commit](./images/git-vscode-commit.png)
コミットメッセージを入力し，コミットボタンを押すと、コミットが完了します。

## プッシュ
![git-vscode-push](./images/git-vscode-push.png)

`Source Control`から、`branchの発行`をクリックしてsshキーのパスフレーズを入力します。

## プルリクエスト（PR）
![git-vscode-pr](./images/git-vscode-pr.png)

githubの拡張機能をインストールすると、VScode上でプルリクエストを作成することができます。

`Github Pull Request`で検索してみて下さい．
