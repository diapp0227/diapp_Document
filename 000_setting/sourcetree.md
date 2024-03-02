# SourceTree
git管理を行いたいので、わかりやすいGUIでgit操作ができるツールを利用する

## インストール手順

公式サイトからダウンロード

https://www.sourcetreeapp.com/

ダウンロード出来たら、インストーラーの手順通りに進めていく

* 参考: https://prog-8.com/blogs/how_to_use_sourcetree

## 使い方 

### リポジトリ―のクローン

1. 画面上部の「Clone」を選択
2. 「URL」の入力欄に任意のgithubのパスを入力 (ここでは~diapp_Document.git)
3. 「保存先のパス」の入力欄にローカルパスを入力
(前もって空のフォルダを作成して、作成したフォルダを選択するのが一番管理が楽)
4. 「名前」の入力欄を入力
5. 「クローン」を押下

![スクリーンショット 2024-02-27 200027](https://github.com/diapp0227/diapp_Document/assets/161457009/203eacfc-5363-461b-b2b3-cc77a1a0f05b)

### Github設定

そのままだとpullはできてもpushができなかったので色々設定

1. git > Config 設定 

<img width="691" alt="image" src="https://github.com/diapp0227/diapp_Document/assets/161457009/d6663363-5898-4e17-90bd-191d2e920b4a">

2. githubの「personal access token」を作成する

https://qiita.com/setonao/items/28749762c0bc1fbbf502

3. sourcetreeのリモートリポジトリの設定

<img width="626" alt="image" src="https://github.com/diapp0227/diapp_Document/assets/161457009/b941acb5-3d51-4e2c-81e7-43644d4d4fcf">

4. sourcetreeのアカウント設定で 2のトークンをパスワードとして設定する

#### その他参考サイト

* SSHキー・リモートURLの設定

https://tks2.co.jp/2021/01/18/github-ssh/

* 自分の場合は、Hostキーの置き換えを行う必要があった

https://blog.foresta.me/posts/update-known-hosts-fot-github/

* pushできなかったので、リモートURLの設定を見直し


