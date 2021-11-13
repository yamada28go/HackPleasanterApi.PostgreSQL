# HackPleasanterApi.PostgreSQL

## これは何?

PleasanterをPostgreSQLで直接操作するときに使用するViewを生成するコードとなります。
HackPleasanterApiCliコマンドを使用することで、プリザンターのサイトパッケージからサイトに最適化されたViewを生成する事ができます。

[HackPleasanterApiCli](https://github.com/yamada28go/HackPleasanterApiCli)

## ディレクトリ構成

| No | ディレクトリ名  | 概要  |
| --- | --- | --- |
| 1 |  Templates | [HackPleasanterApiCli](https://github.com/yamada28go/HackPleasanterApiCli)でグルーコードを生成するときに使用するテンプレートが格納されています。 |


## 使い方

### 1: グルーコードを生成

Pleasanterのサイトパッケージ(JSON)をエクスポートとして、グルーコード生成対象となるテーブル、インターフェースを決定します。

これらの動作の詳細は以下コマンドを参照してください。

[HackPleasanterApiCli](https://github.com/yamada28go/HackPleasanterApiCli)

### 2: Viewの生成

本テンプレートを使ってViewを生成します。


