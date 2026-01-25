---
description: 如何更新和维护 Hugo 博客
---

# Hugo 博客日常维护指南

## 📝 发布新文章

### 创建新博客文章

```bash
cd /Users/sunxiujie/Downloads/xiujie-blog

# 创建博客文章
hugo new blogs/文章名称.md

# 创建随笔
hugo new essays/随笔名称.md
```

### 编辑文章

1. 打开 `content/blogs/文章名称.md`
2. 修改 `draft: false` 以发布文章
3. 编写 Markdown 内容

### 本地预览

```bash
# 预览（包含草稿）
hugo server -D

# 预览（仅发布的文章）
hugo server
```

访问 http://localhost:1313 查看效果

---

## 🚀 发布到网站

// turbo-all

```bash
cd /Users/sunxiujie/Downloads/xiujie-blog

# 1. 添加更改
git add .

# 2. 提交更改
git commit -m "Add new post: 文章标题"

# 3. 推送到 GitHub
git push
```

GitHub Actions 会自动构建并部署到 https://sxj2003.github.io

---

## 📁 常用文件位置

| 内容 | 路径 |
|------|------|
| 配置文件 | `hugo.yml` |
| 博客文章 | `content/blogs/` |
| 随笔 | `content/essays/` |
| 关于我 | `content/about/index.md` |
| 静态资源 | `static/` |
| 图片 | `static/images/` |

---

## 🖼️ 添加图片

1. 将图片放入 `static/images/` 目录
2. 在文章中引用：`![描述](/images/图片名.jpg)`

---

## ⚙️ 常用配置修改

| 修改项 | 文件 | 位置 |
|--------|------|------|
| 网站标题 | `hugo.yml` | `title:` |
| 个人介绍 | `hugo.yml` | `profileMode.subtitle:` |
| 社交链接 | `hugo.yml` | `socialIcons:` |
| 导航菜单 | `hugo.yml` | `menu.main:` |
| 关于我 | `content/about/index.md` | 整个文件 |

---

## 🔧 故障排除

### 本地预览报错
```bash
# 清理缓存后重新构建
hugo --gc --cleanDestinationDir
hugo server
```

### GitHub Actions 构建失败
1. 访问 https://github.com/sxj2003/sxj2003.github.io/actions
2. 查看失败的构建日志
3. 根据错误信息修复

### 更新主题
```bash
cd themes/PaperMod
git pull
```
