## 分支

分支是使用 Git 工作的一个重要部分。你做的任何提交都会发生在当前 ` checked out` 到的分支上。使用 `git status` 查看那是哪个分支。

### 创建新分支

```bash
git branch [branch-name] 
```

### 切换分支

```bash
# 切换到指定分支并更新工作目录(working directory)。
git checkout [branch-name]
```

### 合并分支

```bash
# 将指定分支的历史合并到当前分支。这通常在拉取请求(PR)中完成，但也是一个重要的 Git 操作。
git merge [branch]
```

### 删除指定的分支

```bash
git branch -d [branch-name]
```
