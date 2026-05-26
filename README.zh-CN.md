# Simple

[English](README.md) | [中文](README.zh-CN.md)

一款为 [Typecho](https://typecho.org/) 设计的轻量、极简主题，由 JRTx 设计。基于 Bootstrap 构建，提供简洁的博客布局和移动端适配。

## 预览

![Simple 主题预览](screenshot.png)

## 功能特点

- **极简设计** -- 干净、无干扰的阅读体验
- **响应式布局** -- 支持移动端，自动检测设备类型
- **基于 Bootstrap** -- 使用 Bootstrap 3.1.1 确保一致的样式风格
- **固定导航栏** -- 顶部导航栏包含博客和关于页面链接
- **带日期的文章列表** -- 文章以简洁列表形式展示，附带发布日期
- **自定义页面** -- 支持 Typecho 自定义页面（如关于页面）
- **轻量** -- 极少的 CSS，不依赖任何 JavaScript 框架

## 环境要求

- [Typecho](https://typecho.org/) 博客引擎
- PHP 7.0+

## 安装方法

1. 将仓库下载或克隆到 Typecho 主题目录：
   ```bash
   cd /path/to/typecho/usr/themes/
   git clone https://github.com/jrtxio/simple.git
   ```

2. 登录 Typecho 后台管理面板。

3. 进入 **控制台 > 外观**，启用 **Simple** 主题。

## 主题结构

```
simple/
  index.php        # 博客首页（文章列表）
  post.php         # 文章详情页
  page.php         # 自定义页面
  iheader.php      # 首页头部（包含导航栏）
  pheader.php      # 文章/页面头部
  css/
    bootstrap.min.css        # Bootstrap 核心
    bootstrap-theme.min.css  # Bootstrap 主题
    home.css                 # 首页样式
    main.css                 # 文章/页面样式
  images/
    logo.svg       # 站点 Logo
    Octocat.jpg    # 网站图标
  screenshot.png   # 主题预览图
```

## 自定义

- 编辑 `css/home.css` 和 `css/main.css` 修改外观样式
- 修改 `iheader.php` 调整导航链接
- 替换 `images/Octocat.jpg` 为自己的网站图标

## 许可证

本项目目前未包含许可证文件。
