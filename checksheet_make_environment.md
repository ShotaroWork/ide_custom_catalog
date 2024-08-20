# azuredeploy.json作成時の注意

## Storageを扱う場合
-"accessTier": "TransactionOptimized",が記載されていないか？特にファイル共有が存在する場合

## EventHubを扱う場合
-"sku"がBasicになっていないか？

## PostgreSQLを扱う場合
- 管理者名とパスワードを変数として追加しているか？

## その他
-apiVersionは適正なものになっているか？