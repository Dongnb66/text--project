---
name: git-helper
description: "Git 辅助技能：一键提交、推送、拉取、查看状态"
description_zh: "Git 辅助技能：一键提交、推送、拉取、查看状态"
description_en: "Git helper skill: one-click commit, push, pull, status"
version: 1.0.0
allowed-tools: Bash,Read,Write
---

# Git Helper Skill

个人 Git 辅助技能，提供快捷的 Git 操作。

## 功能列表

### 1. 查看状态
```bash
git status
git log --oneline -5
```

### 2. 一键提交推送
当用户说「提交推送」或「同步」时：
1. `git add .`
2. `git commit -m "<用户提供的备注>"`
3. `git push origin main`

### 3. 拉取更新
当用户说「拉取」或「更新」时：
```bash
git pull origin main
```

### 4. 查看远程信息
```bash
git remote -v
git branch -a
```

## 同步说明

本技能文件存储在 GitHub 仓库 `Dongnb66/text--project` 中。
修改后通过以下命令同步：
```bash
cd /c/Users/dong/Desktop/text-project
git add .workbuddy/
git commit -m "更新技能: git-helper"
git push origin main
```
