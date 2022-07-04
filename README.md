# VketCloudSDKドキュメント制作へようこそ
このリポジトリは、VketCloudSDKのドキュメントを管理するリポジトリです。

# Contribution policy
社外コントリビューターの参加も絶賛受付中です。
誤字脱字の修正から文言のブラッシュアップまで、どんな些細なリクエストであっても、気軽にコミットいただいて結構です。
なお、プルリクエストされた時点で、以下の規約にご同意いただいたとみなします。ご了承ください。

- プルリクエストが承認されたとしても、いかなる報酬も発生しません。
- プルリクエストは却下される場合があり、かつ将来にわたって再度修正されることがあります。
- コミット内容に関して、著作権はHIKKYに帰属します。
- 悪質なコミットや嫌がらせに関しては、法的なしかるべき処置を持って対応します。

# 執筆環境の導入
執筆環境の導入は、以下の二通りが可能です。

## pipを使う
もっともシンプルな環境構築になります。コマンドから執筆に必要な環境を導入していきます。
使用するフレームワークおよびプラグインは、以下の通りです。

- git
- mkdocs
- mike
- i18l
- mkdocs material

これらのパッケージを以下のように

## dockerを使う
コマンドを使った導入以外にも、dockerによる環境構築も可能です。
dockerを使用する場合は、あらかじめdockerとdocker-composeがインストールされている必要があります。
dockerの詳しい使い方は省略しますが、docker-compose.ymlがあるディレクトリに移動し、docker-compose upでコンテナを起動します。

# mkdocsを起動する
mkdocsを起動するには、

```
cd 〇〇〇/VketCloudSDK/source #mkdocs.ymlがあるディレクトリ
mkdocs serve
```

とコマンドを打ち、ブラウザからhttp://127.0.0.1:8000/を開いてください。

また、このドキュメントはmikeによってバージョン管理をしています。バージョンを切り替え機能を含めて起動するには、

```
cd 〇〇〇/VketCloudSDK/source #mkdocs.ymlがあるディレクトリ
mike serve
```

で起動することができます。

# お問い合わせ
執筆環境の導入や掲載内容についてのお問い合わせは、このリポジトリにissueを立てていただくか、VketCloudSDKのDiscordサーバー内にて、お問い合わせください。