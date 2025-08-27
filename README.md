# 我的博客

这是一个简单的个人博客，使用HTML、CSS和JavaScript构建，适合用于分享读书心得、观影感受和生活随笔等内容。

## 博客特点

- 简单明快的设计风格
- 支持分类展示文章（读书笔记、观影心得、生活随笔）
- 包含首页、文集和关于页面
- 响应式设计，适配不同设备

## 如何部署到GitHub Pages

1. 在GitHub上创建一个新的仓库，命名为`username.github.io`（其中`username`是你的GitHub用户名）

2. 将本地的博客文件推送到这个仓库

```bash
# 初始化git仓库
git init

# 添加所有文件
git add .

# 提交更改
git commit -m "Initial commit"

# 添加远程仓库
git remote add origin https://github.com/username/username.github.io.git

# 推送到GitHub
git push -u origin master
```

3. 等待几分钟，你的博客就会在`https://username.github.io`上可见

## 如何添加新文章

1. 在根目录下创建一个新的HTML文件，文件名可以是`article5.html`、`article6.html`等

2. 复制现有文章的HTML结构，并修改标题、日期、内容等信息

3. 在`articles.html`中添加新文章的链接和预览信息

4. 如果是新的分类，需要在`articles.html`中添加对应的分类标签

## 如何修改样式

你可以通过修改`style.css`文件来改变博客的样式。这个文件包含了所有的CSS样式定义，你可以根据自己的喜好进行修改。

## 如何添加图片

1. 在根目录下创建一个`images`文件夹

2. 将图片文件放入这个文件夹

3. 在文章中使用相对路径引用图片，例如：

```html
<img src="images/example.jpg" alt="示例图片">
```

## 注意事项

- 请确保所有文件都使用UTF-8编码，以避免中文显示问题
- 在修改文件时，请备份原始文件，以便在出现问题时可以恢复
- 如果需要添加更多功能，你可以学习一些前端框架，如React、Vue等

## 许可证

本博客模板采用MIT许可证，你可以自由使用、修改和分发。