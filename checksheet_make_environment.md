# azuredeploy.json作成時のチェックリスト(2024 8/20作成)

## "type": "Microsoft.Storage/storageAccounts/fileServices/shares"について
-"accessTier": "TransactionOptimized"が記載されていないか？あれば記載を消す事。

## "type": "Microsoft.EventHub/namespaces"について
-"sku":"Standard"になっているか？

## "flexibleServers_admin_name"
- "flexibleServers_admin_name":{"defaultValue": "watchman","type": "String"}が"parameters"として存在するか？

## "flexibleServers_admin_password"
- "flexibleServers_admin_password": {"defaultValue": "cloudG2024","type": "String"}が"parameters"として存在するか？

## その他
-apiVersionは適正なものになっているか？