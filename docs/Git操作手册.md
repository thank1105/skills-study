# Git 操作手册

## 基本工作流

### 1. 修改文件后，提交更改
```bash
git add .
git commit -m "你的提交信息"
```

### 2. 推送到GitHub
```bash
git push origin main
```

## 常用命令速查

| 操作 | 命令 |
|------|------|
| 查看修改状态 | `git status` |
| 查看修改内容 | `git diff` |
| 添加所有文件 | `git add .` |
| 添加指定文件 | `git add 文件名` |
| 提交更改 | `git commit -m "信息"` |
| 推送到GitHub | `git push origin main` |
| 查看提交历史 | `git log --oneline` |
| 拉取最新代码 | `git pull origin main` |
| 查看远程仓库 | `git remote -v` |

## 完整工作流示例

```bash
# 1. 修改文件（在编辑器中）

# 2. 检查状态
git status

# 3. 添加修改
git add .

# 4. 提交
git commit -m "更新说明"

# 5. 推送
git push origin main
```

## 实用技巧

### 查看详细的修改内容
```bash
git diff
```

### 查看完整的提交历史
```bash
git log
```

### 只提交某个文件
```bash
git add 文件名
git commit -m "提交信息"
git push origin main
```

### 撤销未提交的修改
```bash
git checkout -- 文件名
```

### 修改最后一次提交信息
```bash
git commit --amend -m "新的提交信息"
```

## 注意事项

- ✓ 提交信息要清晰简洁，说明做了什么改动
- ✓ 经常推送，避免本地改动过多
- ✓ 如果多人协作，推送前先 `git pull` 拉取最新代码
- ✓ 在提交前用 `git status` 检查要提交的文件
- ✓ 用 `git diff` 查看具体改动内容

## 仓库信息

- **仓库地址**：https://github.com/thank1105/skills-study.git
- **主分支**：main
- **用户名**：thank1105
