# 暗号資産とNFTのトラブル集 | CGTF

[https://cgtf.github.io/user-guidance/](https://cgtf.github.io/user-guidance/)

## 開発環境

- Hugoのインストール
- git submoduleのアップデート
- npmパッケージのインストール

### Clone

```
git clone git@github.com:cgtf/user-guidance.git
```

### Hugo

Hugo（静的サイトジェネレーター）を利用しています。開発にはHugoが必要です。インストールは[こちら](https://gohugo.io/getting-started/installing)をご確認ください。

### npm

```
npm install
```

npm scriptsによって以下が実行されます。

- `git submodule update --init --recursive`
    - Hugoのテーマに[Docsy](https://www.docsy.dev/)を利用しています。gitのサブモジュールになっています。
- `(cd themes/docsy && npm install)`
    - docsyの依存解決

## 動作確認

ローカル環境で動作確認するには、下記コマンドを実行してから[http://localhost:1313/](http://localhost:1313/)にアクセスします。LiveReloadにより、コードに変更を加えて保存するとブラウザに反映されます。

```
hugo server
```

※ `--buildFuture`, `--buildDrafts`, `--buildExpired` を付けて実行すると、公開日付が未来の記事、下書きの記事、公開期限切れの記事も表示されます。

## ファイルを生成する

サーバーに配置して公開するためのHTMLファイルを生成するには、下記コマンドを実行します。ファイルは `public` フォルダに生成されます。

```
hugo
```

※ `--buildFuture`, `--buildDrafts`, `--buildExpired` を付けて実行すると、公開日付が未来の記事、下書きの記事、公開期限切れの記事も生成されます。