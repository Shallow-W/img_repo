# img_repo / 图片仓库

> A repository specifically for storing images used in my notes
> 
> 这是一个专门用来放图片的仓库，用于给我的笔记显示图片

## 📖 Purpose / 目的

This repository serves as a centralized image hosting service for my markdown notes. Images stored here can be referenced in various note-taking applications and platforms.

这个仓库作为我的markdown笔记的集中图片托管服务。存储在这里的图片可以在各种笔记应用程序和平台中引用。

## 📁 Directory Structure / 目录结构

```
img_repo/
├── images/
│   ├── screenshots/    # Screen captures / 屏幕截图
│   ├── diagrams/       # Technical diagrams / 技术图表
│   ├── icons/          # Icons and small images / 图标
│   └── misc/           # Miscellaneous / 其他
└── README.md
```

## 🚀 Usage / 使用方法

### Adding Images / 添加图片

1. Upload your image to the appropriate directory under `images/`
2. Commit and push to the repository
3. Use the raw GitHub URL in your markdown notes

### 1. 将图片上传到 `images/` 下的相应目录
### 2. 提交并推送到仓库
### 3. 在markdown笔记中使用GitHub原始URL

### Referencing Images / 引用图片

Use the following format in your markdown files:

在markdown文件中使用以下格式：

```markdown
![Image Description](https://raw.githubusercontent.com/Shallow-W/img_repo/main/images/category/your-image.png)
```

**Example / 示例:**

```markdown
![Login Screenshot](https://raw.githubusercontent.com/Shallow-W/img_repo/main/images/screenshots/login-page.png)
```

## 📝 Naming Convention / 命名规范

- Use descriptive, lowercase names with hyphens / 使用描述性的、小写的名称，用连字符分隔
- Include date for time-sensitive images (optional) / 为时间敏感的图片包含日期（可选）
- Examples / 示例:
  - `user-authentication-flow.png`
  - `2026-01-database-diagram.jpg`
  - `app-icon-v2.svg`

## 🎨 Supported Formats / 支持的格式

- PNG (recommended for screenshots and diagrams / 推荐用于截图和图表)
- JPG/JPEG (recommended for photos / 推荐用于照片)
- GIF (for animations / 用于动画)
- SVG (for vector graphics / 用于矢量图形)
- WebP (for optimized web images / 用于优化的网页图片)

## 📋 Best Practices / 最佳实践

1. **Optimize images** before uploading to reduce file size / 上传前优化图片以减小文件大小
2. **Use meaningful names** that describe the image content / 使用描述图片内容的有意义的名称
3. **Organize by category** to keep the repository clean / 按类别组织以保持仓库整洁
4. **Delete unused images** to avoid clutter / 删除未使用的图片以避免混乱

## 📄 License / 许可证

All images in this repository are for personal use only.

本仓库中的所有图片仅供个人使用。
