# README 两个版本

- [朴素版](../README.minimal.md)：保留风格化之前的 README，包括来访计数器。
- [连线世界版](../README.styled.md)：参考博客主页，包含蓝青与红黑封面、斜切导航和双栏正文。左栏为个人介绍与平台入口，右栏为技术栈；动画与来访计数器并排展示。
- [仓库首页](../README.md)：当前使用连线世界版。

两版均已纳入 Git，风格化图片保存在 `img/readme/`。来访计数器使用相同的账号和样式。

在仓库目录使用 PowerShell 切换首页：

```powershell
# 使用朴素版
Copy-Item -LiteralPath README.minimal.md -Destination README.md

# 使用连线世界版
Copy-Item -LiteralPath README.styled.md -Destination README.md
```

切换后提交并推送 `README.md` 即可更新 GitHub 首页。后续编辑时，同步更新对应版本文件，便于再次切换。
