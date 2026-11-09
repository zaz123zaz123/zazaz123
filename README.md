# hello-world

我在 GitHub 上的第一个仓库，用来走一遍「创建仓库 → 提交第一个更改」的流程。

## 这个仓库是什么

一个最小可用的起点：只有这份 README，没有代码。它的作用是把 Git 的几个核心概念串起来——仓库（repository）、暂存区（staging area）、提交（commit）、分支（branch）。

## 本地怎么用

```bash
git status          # 看工作区有什么改动
git add README.md   # 把改动放进暂存区
git commit -m "..." # 生成一个提交快照
git log --oneline   # 看提交历史
```

## 下一步

- 在 GitHub 上新建一个空仓库（不要勾选初始化 README）
- 关联远端并推送：

```bash
git remote add origin https://github.com/<你的用户名>/hello-world.git
git push -u origin main
```

## 备注

仓库内的提交身份是占位的（`Administrator <administrator@localhost>`），推送前建议改成你自己的 Git 身份：

```bash
git config user.name "你的名字"
git config user.email "你的邮箱"
```
