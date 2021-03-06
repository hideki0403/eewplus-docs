---
title: スラッシュコマンドが使えない
slug: /troubleshooting/slashcommand
sidebar_position: 2
---

### コマンドの候補が表示されない場合
#### 他のBotのコマンド候補は表示されるが、EEWPlusBotの候補だけ表示されない
Botにスラッシュコマンドに関する権限が付与されていない可能性があります。  
[こちら](/invite)からEEWPlusを再度導入してください。  

#### コマンドの候補すら表示されない (どのBotの候補も表示されない)
ユーザーにスラッシュコマンドの権限が付与されていない可能性があります。  
以下の手順に従って、操作を行うことでスラッシュコマンドを有効化できます。
  
① サーバーの設定を開く  
② 「ロール」を選択し、任意のロール（スラッシュコマンドを有効にしたいロール）をクリックする  
③ PCの場合は「権限」タブに移動する  
④ 権限の中にある「アプリコマンドを使う」をONにする  
  
これで設定は完了です。

#### 上記2つを試しても表示されない
チャンネルの設定でスラッシュコマンドが無効化されている可能性があります。  
以下の手順に従って、操作を行うことでスラッシュコマンドを有効化できます。  
  
① 該当のチャンネルの設定を開く  
② 「権限」に移動する  
③ @everyone(または任意のロール)の「アプリコマンドを使う」をONにする  

### Botから返信が来ない場合
「[地震情報などが投稿されない](message.md)」の「Botに権限が付与されていますか？」を参考に、Botに権限を付与してください。

### エラーが表示された場合
以下の画像のようにエラーが表示された場合はBot側で問題が発生している可能性があります。  
しばらく時間を置いてから再度お試しください。  
![img](/img/docs/troubleshooting/slashcommand/error.png)

### それでも解決しない場合
[こちら](/invite)からEEWPlusを再度導入してください。  