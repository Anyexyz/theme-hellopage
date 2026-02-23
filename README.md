# Theme HelloPage

HelloPage 是一款简洁的导航页主题，适用于 Halo 系统，可用于快捷搭建一个导航站。

![效果图](img/1716922588945.png)

<div align="center">

移植于 [5IUX搜索 - 导航版](https://sou.5iux.cn/)

</div>

## 特性

- 🎨 **简洁美观**: 现代化的界面设计，支持自定义背景图/视频
- 🔍 **多搜索引擎**: 内置多个搜索引擎，支持自定义添加
- 🔗 **链接分组**: 依赖 Halo 官方插件 [链接管理](https://www.halo.run/store/apps/app-hfbQg)，支持分组管理和自定义图标
- 📱 **响应式设计**: 完美适配桌面端和移动端
- ⚙️ **高度可配置**: 支持自定义标题、副标题、背景、搜索引擎、备案信息等
- ♿ **无障碍访问**: 添加了 ARIA 标签，提升可访问性
- 🔒 **安全优化**: 改进了 XSS 防护，添加了 SRI 校验支持

## 安装使用

⚠️ **此主题需要安装 Halo 的官方插件 [链接管理](https://www.halo.run/store/apps/app-hfbQg)** 才能正常使用。

> 本主题适合作为副主题使用。安装并填写主题相关配置后，可以在站点地址后加上 `?preview-theme=theme-hellopage` 来访问。无需启用本主题，因此不会影响到您现在所使用的主题。

### 主要功能

#### 1. 搜索引擎配置
预置多个搜索引擎，包括：
- 秘塔AI搜索
- 百度
- Bing必应
- DuckDuckGo
- GitHub
- Google
- Linux 命令
- 百度翻译
- Google翻译
- iconfont
- Crx搜搜

可自定义添加更多搜索引擎。

#### 2. 链接分组管理
- 支持自定义分组图标（SVG 或图片）
- 控制分组在 HelloPage 中显示
- 支持登录可见功能
- 支持链接关联文章

#### 3. 自定义样式
- 自定义首页标题和副标题
- 支持图片或视频背景（MP4格式）
- 背景位置可选择跟随滚动或固定

#### 4. 备案设置
- ICP 备案号配置
- 公安联网备案号配置

#### 5. 代码注入
- 搜索框下方代码注入
- 页面底部代码注入

### 自定义分组图标

![自定义分组图标](img/1716923218830.png)

### 链接关联文章

![链接关联文章](img/1716923270559.png)

## 更新日志

### v1.1.2 (最新)
- ✨ 优化代码结构，提取公共模板片段
- ⚡ 性能优化：优化时间更新脚本间隔
- ♿ 添加无障碍访问支持（ARIA 标签）
- 🎨 改进响应式视频背景
- 🖱️ 移除滚动条隐藏样式，改为美化滚动条
- 🧹 清理代码：移除 !important，统一代码风格
- 📝 格式化压缩的 JavaScript 代码
- 🔒 安全优化：添加 encodeURIComponent 编码
- 🗑️ 移除冗余文件（sou.js、svg.js）
- 📦 使用 CDN 加载 Bootstrap 和 jQuery
- 🐛 修复文章页和独立页面的模板引用

### v1.1.1
- 添加分组、链接登录可见控制

### v1.1.0
- 初始版本

## 浏览器支持

- Chrome (推荐)
- Edge
- Firefox
- Safari
- 移动端浏览器

## 致谢

- [Halo](https://halo.run/)
- [5IUX搜索 - 导航版](https://sou.5iux.cn/)
- [六零导航页](https://hao.lylme.com/)
- [Ryan Wang](https://ryanc.cc/)
- [张洪Heo](https://github.com/zhheo)
- [困困鱼](https://github.com/chengzhongxue)

## 技术栈

- [Thymeleaf](https://www.thymeleaf.org/) - 模板引擎
- [Bootstrap](https://getbootstrap.com/) - CSS 框架
- [jQuery](https://jquery.com/) - JavaScript 库

## 许可证

[MIT License](LICENSE)

## 欢迎关注

- [Anyeの小站](https://www.anye.xyz/)
