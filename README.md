# Assets 图片资源库

这个仓库用于存储和提供通过 jsDelivr CDN 加速访问的图片资源。

## 项目用途

本项目主要用于：
- 利用 [jsDelivr](https://www.jsdelivr.com/) 作为免费的内容分发网络(CDN)
- 为博客、网站或应用程序提供快速的图片加载体验
- 全球范围内的资源访问加速
- 提供稳定可靠的图片链接

## 目录结构

- `/avatar`: 存储头像图片
- `/i/moment`: 存储照片和其他图片资源

## 如何使用

### 通过 jsDelivr 访问 GitHub 上的图片

基本格式:
```
https://cdn.jsdelivr.net/gh/用户名/仓库名@分支/文件路径
```

例如，访问本仓库中的图片:
```
https://cdn.jsdelivr.net/gh/username/assets@main/avatar/avatar1.webp
https://cdn.jsdelivr.net/gh/username/assets@main/i/moment/照片名称.jpg
```

### 优势

1. **全球加速**: jsDelivr拥有全球超过500个节点，提供快速的访问速度
2. **永久缓存**: 一旦文件发布，CDN会永久缓存
3. **免费使用**: 对开源项目完全免费
4. **自动压缩**: 自动提供文件压缩和优化
5. **防盗链功能**: 保护您的资源不被盗用

## 刷新缓存

如果您更新了图片但 CDN 仍然提供旧版本，可以通过以下 URL 刷新缓存:
```
https://purge.jsdelivr.net/gh/username/assets@main/文件路径
```

## 注意事项

- 建议使用特定的 git 标签或 commit hash 而不是分支名，以确保 CDN 缓存的稳定性
- 不要删除已经发布的文件，以免破坏已有的引用
- 图片格式优先考虑 WebP、AVIF 等现代压缩格式，以提供更好的性能

## 相关链接

- [jsDelivr官网](https://www.jsdelivr.com/)
- [jsDelivr文档](https://www.jsdelivr.com/documentation) 