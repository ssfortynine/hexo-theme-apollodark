# 🌑 Apollo Dark

**English** | [中文](#apollo-dark-zh)

Apollo Dark is a dark-themed fork of [hexo-theme-apollo](https://github.com/pinggod/hexo-theme-apollo), redesigned for a modern dark-mode experience.

![hexo-theme-apollodark](./doc/demo.png)

## Documentation
- [English Document](./doc/doc-en.md)
- [中文文档](./doc/doc-zh.md)

## Installation

```bash
# Create a new blog directory | 创建博客目录
hexo init Blog 
cd Blog 
npm install

# Install required plugins | 安装必要依赖
npm install --save hexo-renderer-jade hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive

# Clone this theme | 克隆主题
git clone https://github.com/ssfortynine/hexo-theme-apollodark.git themes/apollodark
```

## Activation

Modify `_config.yml` and set the `theme` to `apollodark`:

```yaml
theme: apollodark

# Archive page settings (Requires hexo-generator-archive)
# 归档页面配置
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

## Update

```bash
cd themes/apollodark 
git pull
```

## Features & Contributions

This version is a fork of `hexo-theme-apollo` with the following enhancements:
- **Dark Mode**: Default dark background theme.
- **TOC Support**: Integrated Table of Contents for articles.
- **Comments**: Built-in support for comment systems.
- **Mobile Optimized**: Improved Table of Contents display on mobile devices.
- **Tags**: Added tag cloud and tag display functionality.

Original version credits: [WhoKnowInfinity/hexo-theme-apollo](https://github.com/WhoKnowInfinity/hexo-theme-apollo)

## License
MIT

---

<a name="apollo-dark-zh"></a>

# 🌑 Apollo Dark (中文版)

本主题 Fork 自 [hexo-theme-apollo](https://github.com/pinggod/hexo-theme-apollo)，并重制为深色模式。

## 文档
- [中文文档](./doc/doc-zh.md)
- [English Document](./doc/doc-en.md)

## 安装

```bash
hexo init Blog 
cd Blog 
npm install
npm install --save hexo-renderer-jade hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
git clone https://github.com/ssfortynine/hexo-theme-apollodark.git themes/apollodark
```

## 启用

修改 `_config.yml` 的 `theme` 配置项为 `apollodark`:

```yaml
theme: apollodark

# 在归档页面显示所有文章
# 需要上面安装的 hexo-generator-archive 插件支持
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

## 更新

```bash
cd themes/apollodark 
git pull
```

## 贡献与功能说明

该版本在原版基础上增加了以下功能：
- **深色模式**：默认主题背景颜色为暗色。
- **目录功能**：增加文章 TOC 目录。
- **评论功能**：增加评论系统支持。
- **移动端优化**：修复并优化了移动端目录显示逻辑。
- **标签功能**：增加 Tags 分类页面及标签显示。

原版本仓库参考：[WhoKnowInfinity/hexo-theme-apollo](https://github.com/WhoKnowInfinity/hexo-theme-apollo)

## 开源协议
MIT
