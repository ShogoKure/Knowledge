# Gitコマンドのサマリー

## " Reference "

[公式ドキュメント](https://git-scm.com/docs)
[Git チートシート](https://training.github.com/downloads/ja/github-git-cheat-sheet.pdf)
[Git Hub Docs](https://docs.github.com/ja)

## " git cloen "

### 既存のリポジトリをクローンする

```shell
git clone [RepositoryURL]
```

デフォルトでカレントディレクトリに保存される

## " git branch "

### 現在のリポジトリ上のすべてのローカルブランチを一覧で表示

```shell
git branch
```

### 新規ブランチを作成

```shell
git branch [BranchName]
```

### 指定されたブランチを削除

```shell
git branch -d [BranchName]
```

### リモートブランチを含めた全てのブランチを一覧で表示

```shell
git branch -a
```

### リモートブランチを一覧で表示

```shell
git branch -r
```

### ブランチの一覧表示のカラー変更

```shell
# color
git branch --color

# No color
git branch --no-color
```

## " git log "

### 各ブランチのツリー構造を確認

```shell
git log  --all --graph --decorate --oneline
```

## " git checkout "

### 指定されたブランチに切り替え

```shell
git checkout [BranchName]
```
