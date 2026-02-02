# 给林园园的专属网页

这是一个为你特别定制的网页项目。

## 🌟 项目包含
- **首页**: 浪漫的欢迎界面和打字机效果动画。
- **美好瞬间**: 照片展示墙（你可以替换成真实照片）。
- **想对你说**: 一封电子情书。

## 🚀 如何部署到 GitHub Pages

只需简单几步，就可以让这个网页在互联网上被访问：

1.  **创建仓库**
    - 登录你的 GitHub 账号。
    - 点击右上角的 "+" 号，选择 "New repository"。
    - 仓库名可以叫 `yuanyuan-love` 或其他你喜欢的名字。
    - 勾选 "Add a README file"（可选），然后点击 "Create repository"。

2.  **上传代码**
    - 在你的电脑上，打开这个项目文件夹。
    - 如果你安装了 Git，可以使用命令行推送代码：
      ```bash
      git init
      git add .
      git commit -m "Initial commit - For Yuanyuan"
      git branch -M main
      git remote add origin https://github.com/你的用户名/仓库名.git
      git push -u origin main
      ```
    - 或者，直接在 GitHub 页面点击 "Upload files"，将文件夹中的所有文件拖进去并提交。

3.  **开启 GitHub Pages**
    - 在仓库页面，点击 **Settings** (设置)。
    - 在左侧侧边栏找到 **Pages**。
    - 在 **Build and deployment** 下的 **Source** 选择 "Deploy from a branch"。
    - 在 **Branch** 下选择 `main` 分支，文件夹选择 `/ (root)`。
    - 点击 **Save**。

4.  **获取链接**
    - 等待几分钟刷新页面，你会看到顶部出现一行字：
      "Your site is live at https://你的用户名.github.io/仓库名/"
    - 复制这个链接发给她吧！

## 📸 如何替换照片
1. 将你的照片放入 `images` 文件夹。
2. 打开 `index.html`。
3. 找到 `<div class="gallery">` 部分。
4. 将 `<div class="photo-placeholder"...>照片 X</div>` 替换为 `<img src="images/你的照片文件名.jpg" alt="描述">`。

祝你成功！❤️
