# アプリの概要
ゆる〜い TODO アプリ

今年日記を買ったが全く続かなかったのでアプリで日記を続けたい

# 仕様

## 日記機能
日付をキーに情報を読み書きできるようにする
memo に 日記の文章を記載する

### タグ
ユーザーがタグを自作できる
タグは種別を設定できる。
- Tag ... Tag1,Tag2,Tag3,,, と インクリメントされている
- タグ名 ... タグ名を自由に入力できる
- 文章(String) ... 日付情報に対して任意で文字を入力できる
- 数字(Float) ... 日付情報に対して数字を入力できるようにする
  - 時間(h・m) ... 統計で計算できるようにする 1時間・1分単位で設定
  - 金額 ... 統計で計算できるようにする
  - 設定なし

## 統計
保存した情報を 1週間・1ヶ月・１年単位で 統計させる
- 棒グラフ
- 円グラフ

## アカウント認証 
ログイン機能をつける
- Android・iOS・Webで開発するので保存した情報を同期させたい
- Firebase Authentication を利用したい
※参考
https://firebase.google.com/docs/auth/flutter/start?hl=ja
https://www.flutter-study.dev/firebase-app/authentication

## 情報共有

- Firebase Realtime Database を利用する
https://firebase.google.com/docs/database/flutter/start?hl=ja
https://zenn.dev/snova301/books/6df29a230d681f/viewer/433782
https://blog.flutteruniv.com/flutter-firebase/#toc1
