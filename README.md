# タスク管理

GitHub Issuesを使用したタスク管理システムです。

## 使い方

### デイリータスク

1. Issues ページで「New Issue」をクリック
2. 「デイリータスク」テンプレートを選択
3. タスク一覧と日付を記入
4. 優先度ラベルを設定（`priority:high` / `priority:medium` / `priority:low`）
5. Issueを作成

### プロジェクトタスク

1. Issues ページで「New Issue」をクリック
2. 「プロジェクトタスク」テンプレートを選択
3. プロジェクト名、メインタスク、子タスクを記入
4. 優先度ラベルを設定（`priority:high` / `priority:medium` / `priority:low`）
5. Issueを作成

#### 子タスクの記入方法

```markdown
## タスク1の子タスク
- [ ] 子タスク1-1
- [ ] 子タスク1-2

## タスク2の子タスク
- [ ] 子タスク2-1
- [ ] 子タスク2-2
```

チェックボックスは、タスクが完了したら `- [x]` に変更することで進捗を管理できます。

## ラベル

- `daily`: デイリータスク
- `project`: プロジェクトタスク
- `task`: タスク全般
- `priority:high`: 優先度：高
- `priority:medium`: 優先度：中
- `priority:low`: 優先度：低

