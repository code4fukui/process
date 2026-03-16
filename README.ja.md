# process
The Japanese README is here: [README.ja.md](README.ja.md)

A `process` object emulator for Deno / ES modules.

## 機能
- Denoに対してNode.js `process`オブジェクトをエミュレートする`process`オブジェクトを提供します
- `argv`、`stderr`、`stdout`、`exit`、`on`、`env`、`platform`プロパティを含みます
- 提供されたオブジェクトを通じて`stderr`と`stdout`に書き込むことができます

## 使用方法
`process`エミュレーターを使用するには、`process.js`ファイルからデフォルトのエクスポートをインポートします:

```javascript
import process from './process.js';
```

その後、`process`オブジェクトおよびその属性とメソッドにアクセスすることができます。

## ライセンス
このプロジェクトは [MIT License](LICENSE) のもとで公開されています。
