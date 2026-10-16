# git branch：平行宇宙的开关

## 一句话说明

创建、查看或删除分支，让你能在不影响主线的情况下独立开发。

## 语法

```bash
git branch              # 查看所有本地分支
git branch 分支名        # 创建分支
git checkout -b 分支名   # 创建并立刻切换（最常用）
```

## 示例

```bash
git checkout -b feat/login-page
# 在新分支上改代码、提交，main 分支完全不受影响
git checkout main       # 干完活切回主线
```

## 常见坑

- `git branch 名字` 只创建分支，不会自动切过去，记得用 checkout 或 switch
- 分支名用小写英文 + 斜杠分组，如 feat/login、fix/typo
- 分支是"指针"不是复制，开分支几乎不占空间，放心开

---

📝 贡献者：DevB
