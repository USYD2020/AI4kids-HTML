# GitHub 部署指南

按照以下步骤将您的项目部署到 GitHub Pages：

## 1. 在 GitHub 上创建新仓库

1. 访问 [GitHub](https://github.com) 并登录您的账户
2. 点击右上角的"+"图标，选择"New repository"
3. 在"Repository name"中输入: `ai4kids-html`
4. 确保选择"Public"（如果要公开访问）
5. 不要勾选"Initialize this repository with a README"
6. 点击"Create repository"

## 2. 将本地仓库推送到 GitHub

创建仓库后，GitHub 会显示如何将现有仓库推送到 GitHub 的命令。请在终端中运行类似以下的命令：

```bash
git remote add origin https://github.com/你的用户名/ai4kids-html.git
git branch -M main
git push -u origin main
```

## 3. 设置 GitHub Pages

1. 在 GitHub 上打开您刚刚推送的仓库
2. 点击仓库页面上方的"Settings"选项卡
3. 在左侧导航栏中，点击"Pages"
4. 在"Source"部分，从分支下拉菜单中选择"main"，然后点击"Save"
5. 在 GitHub 上已启用 GitHub Pages 功能：https://usyd2020.github.io/AI4kids-HTML/

如果您希望使用自定义域名，可以在 GitHub Pages 设置页面的"Custom domain"部分输入您的域名，并在您的 DNS 提供商处添加相应的 DNS 记录。

## 注意事项

- 部署可能需要几分钟才能生效
- 如果您更新了代码并推送到 GitHub，网站会自动更新
- 确保 index.html 在仓库的根目录，因为它是 GitHub Pages 默认显示的文件

## 可选：自定义域名

如果您有自己的域名：

1. 在 GitHub Pages 设置中，在"Custom domain"部分输入您的域名
2. 点击"Save"
3. 在您的 DNS 提供商处添加相应的 DNS 记录

GitHub 会自动创建一个 CNAME 文件在您的仓库中，包含您的自定义域名。
