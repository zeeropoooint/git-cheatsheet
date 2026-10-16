# git commit：保存一个版本快照

## 一句话说明

把暂存区的改动记录为一次提交，生成一个可回溯的版本。

## 语法

```bash
git commit -m "提交说明"
```

## 示例

```bash
git add git-commit.md
git commit -m "feat: 新增 git-commit 学习卡片"
```

## 常见坑

- 不加 -m 会弹出编辑器写说明，新手常被卡在 vim 里（退出按 Esc 再输入 :q! 回车）
- 提交说明要写"为什么改"，而不是"改了什么"

---

📝 贡献者：DevA
