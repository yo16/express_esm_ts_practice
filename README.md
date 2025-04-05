# express_esm_ts_practice
Expressで、TypeScriptで、ESMで、index.tsから外部のファイルを読む試行

## 背景
- 別のとあるプロジェクトで、うまくいかないから、シンプルにこの問題だけを切り出して試す。

## 結果
- 特に問題なくできた。
- `node`で実行する
  - `"dev": "node --loader ts-node/esm src/index.ts"`
- `ts-node-dev`を使うと、モジュールが見つからないエラーが出る
  - `"dev": "ts-node-dev --respawn --transpile-only src/index.ts"`

