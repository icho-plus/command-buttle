# COMMAND BATTLE
以下のフォルダに実行可能ファイルがあります。

APP/macOS/commandgame.app

## 目的
GUIしか使ったことのないようなCLI初学者でも楽しく基本的なコマンドを覚えられること

## 特徴
・CLI操作の可視化

・一貫したキーボード操作

## 概要
GUIとのギャップを減らしてCLIで遊ぶことができるため、負担なくコマンド操作を覚えることができます。

画面上にはフォルダを模した黄色の四角形が並んでおり、そのうち１つがプレイヤーの位置を表す青色になっています。基本コマンド"rm", "mkdir", "cd"を用いると、それぞれのコマンドに合った状態に黄色の四角形が変化します。

ゲームではプレイヤー側に見えない敵をフォルダのいずれかに配置し、自分がいる位置のフォルダが消されたときに負けとなるゲーム性を追加しています。

## 入力可コマンド
rmdir+[空白]+[名前] : フォルダ作成（灰色のマスがない場合、黄色のマスを一つ作成）

rm+[空白]+[名前] : フォルダ削除（指定したマスを削除）

cd+[空白]+[名前] : プレイヤーのフォルダ移動（指定したマスの色を青色に変える）

exit : ゲーム途中終了
