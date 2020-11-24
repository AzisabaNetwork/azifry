# アジ鯖マインクラフト

新しいアジ鯖の管理システム

## ⤴ サーバーを起動

```console
$ docker-compose up -d
```

## ⤵ サーバーを停止

```console
$ docker-compose down
```

## ✍ サーバーを編集する

すべてのサーバー設定を管理するには [docker-compose.yml](docker-compose.yml) を編集してください。

各サーバーについては、サーバーごとにフォルダがあり、その中に `assets` と `libs` と `parts` フォルダがあります。

### `assets` と `libs` フォルダについて

この2つのフォルダに明確な違いはありません。

このフォルダ内のすべてのファイルが、一番最初にサーバーに導入されます。

ヒント: プラグインの.jarファイルや、データが完結しているタイプのファイルを使い分けて保存すると便利です。

### `parts` フォルダについて

一旦サーバーを起動した後に、このフォルダ内のファイルで上書きします。

ヒント: 設定ファイルの一部などはこっちに保存すると見やすくて便利です。
