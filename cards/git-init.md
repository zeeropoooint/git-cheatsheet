# git init：创建你的第一个仓库

## 一句话说明

在当前目录创建一个新的 Git 仓库。

## 语法

```bash
git init
```

## 示例

```bash
mkdir my-project
cd my-project
git init
```

## 常见坑

- 不要在已有的仓库里再套一个 `git init`（会变成嵌套仓库）
- 初始化后记得用 `git add` + `git commit` 完成第一次提交

## 小贴士

`git init` 之后会自动创建一个隐藏的 `.git` 文件夹，里面存着你所有的版本历史——别手滑删了它。

---

📝 贡献者：项目管理员
