# レガシーサイト判定Bot
クローリングして、サイトの作りが古いか判定する。

判定結果は、TwitterなどのBotで投稿する。


## システム構成
![システム構成図](images/architecture.png)


## メモ
* リポジトリ名は適当なので、そのうち変更するかも
* デプロイ対象のモジュールが多いので、CIツールなどで自動デプロイしたい
 - CircleCI
 - Google Cloud Container Builder
