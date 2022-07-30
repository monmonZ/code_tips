## collection操作の対比表

| SQL | c#/LINQ | Java(Stream API) | ES6 | 日本語 |
| ---- | ---- | ---- | ---- | ---- |
| WHERE | Where | filter | filter | 抽出 |
| ORDER BY | OrderBy | sorted | * | 並べ替え？ |
| SELECT | Select | map | map | 射影 |
| ---- | ---- | ---- | ---- | ---- |
| / | All | allMatch | every | 全部が条件を満たすか |
| / | Any | anyMatch | some | 条件を満たすものがあるか |

