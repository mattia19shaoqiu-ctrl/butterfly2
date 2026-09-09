# 蝶映穗城 · GitHub Pages 发布包

页面是单文件 H5，照片、主视觉、样式和动画均已内嵌。不需要安装软件、不需要构建。

## 上传与发布

1. 登录 https://github.com ，点击右上角 + → New repository。
2. 仓库名建议填写 `dieying-suicheng`，选择 Public（公开），勾选 Add a README file，点击 Create repository。
3. 进入仓库，选择 Add file → Upload files。
4. 将本文件夹里的 `index.html` 上传到仓库根目录；也可一并上传 `.nojekyll`。不要上传 ZIP 文件，不要把整个 github-pages 文件夹作为子文件夹上传。
5. 点击 Commit changes 保存文件。
6. 进入 Settings → Pages。在 Build and deployment 中将 Source 设为 Deploy from a branch。
7. Branch 选择 main，文件夹选择 / (root)，点击 Save。
8. 等待发布完成，刷新 Settings → Pages，点击 Visit site。这里显示的网址才是可以分享的网页地址。

地址形式为：https://你的GitHub用户名.github.io/dieying-suicheng/
若仓库名不同，网址最后一段也相应改变。

## 上传清单

- index.html：必需。首页及全部内嵌资源。
- .nojekyll：可选。跳过 Jekyll 处理；在 Mac 上通常隐藏。只上传 index.html 也能发布此页面。
- README.md：本说明，不影响页面运行。

## 后续更新

上传新版 index.html，替换同名文件并提交，GitHub Pages 会重新发布，访问地址保持不变。

## 如果出现 404

检查 index.html 是否在 main 分支的最外层；Pages 是否选择 main 和 / (root)；等待部署完成后使用 Pages 设置页给出的 Visit site 地址。仓库的 github.com 地址是代码页面，不是 H5 网页地址。

## 素材与显示

图片已内嵌，不需要另传图片文件夹。字体使用设备可用字体回退。
页面底部收录照片作者与官方资料来源。外部资料照片版权仍归原作者；包装为概念展示。

官方发布说明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
