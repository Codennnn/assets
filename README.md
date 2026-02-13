# Assets 静态资源库

这个仓库用于存储和提供通过 **GitHub Pages** 托管访问的静态文件资源。

## 项目用途

本项目主要用于：

- 利用 [GitHub Pages](https://pages.github.com/) 托管静态资源
- 为博客、网站或应用程序提供图片、字体、CSS 等资源
- 通过自定义域名提供稳定可靠的资源链接

## 目录结构

- `/avatar`: 存储头像图片
- `/css`: 存储样式表（主题/页面样式）
- `/fonts`: 存储网页字体文件（.woff2 等），当前包含 vivoSans、HarmonyOS Sans SC 与 MapleMono 系列
- `/i`: 通用图片资源父目录
  - `/i/moment`: 存储照片、相册类图片等
  - `/i/og`: 存储 Open Graph/社交分享预览图
- `/logos`: 存储 Logo 图片

## 如何使用

### 通过自定义域名访问资源

基本格式:

```
https://assets.leoku.top/文件路径
```

例如，访问本仓库中的资源:

```
https://assets.leoku.top/avatar/avatar1.webp
https://assets.leoku.top/i/moment/照片名称.jpg
https://assets.leoku.top/fonts/vivoSans-Regular.woff2
https://assets.leoku.top/css/discuss-theme-dark.css
```

## 注意事项

- GitHub Pages 有每月 100GB 的带宽限制（软限制）
- 单文件大小限制为 100MB
- 资源更新后可能需要清除浏览器缓存才能看到最新版本
- 建议为重要资源使用版本控制（如 Git tag）

## 相关链接

- [GitHub Pages 文档](https://docs.github.com/en/pages)
- [GitHub Pages 使用限制](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages#usage-limits)
