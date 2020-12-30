# VSCode で PureScript IDE を動かす設定

必要なもの

- VSCode
- Yarn

PureScript IDE （拡張機能）をインストール

```
code --install-extension nwolverson.ide-purescript
```

依存パッケージをインストール

```
yarn
```

ビルド

```
yarn build
```

以上で IDE による型情報の表示やコード補完が効くようになると思います。

## 補足

- `"purescript.addNpmPath": true` でローカルインストールのパッケージを利用
- `"editor.defaultFormatter": "nwolverson.ide-purescript"` で IDE 標準のフォーマッタ Purty が適用される
