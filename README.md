<div align="right">
  语言:
  <a title="简体中文" href="https://github.com/izhaoo/hexo-theme-zhaoo/blob/master/README.md">🇨🇳</a>
  <a title="English" href="https://github.com/izhaoo/hexo-theme-zhaoo/blob/master/README_EN.md">🇺🇸</a>
</div>

<div align="center">
  <a href="https://github.com/izhaoo/hexo-theme-zhaoo/" target="_blank" rel="noopener noreferrer">
    <img src="./source/image/zhaoo-logo.png" alt="zhaoo logo" width="100">
  </a>
</div>

<h3 align="center">一款简约的 Hexo 主题</h3>  

<div align="center">
  <a href="https://github.com/izhaoo/hexo-theme-zhaoo/releases" target="_blank" rel="noopener noreferrer">
    <img alt="releases" src="https://img.shields.io/badge/releases-v1.0.0-blue.svg?style=flat-square&longCache=true">
  </a>
  <a href="https://hexo.io" target="_blank" rel="noopener noreferrer">
    <img alt="hexo" src="https://img.shields.io/badge/hexo-%3E=4.0.0-blue.svg?style=flat-square&logo=hexo&longCache=true">
  </a>
  <a href="https://nodejs.org" target="_blank" rel="noopener noreferrer">
    <img alt="node" src="https://img.shields.io/badge/node-%3E=10.9.0-green.svg?style=flat-square&logo=Node.js&longCache=true">
  </a>
  <a href="(https://github.com/izhaoo/hexo-theme-zhaoo/blob/master/LICENSE" target="_blank" rel="noopener noreferrer">
    <img alt="license" src="https://img.shields.io/badge/license-MIT-green.svg?style=flat-square&longCache=true">
  </a>
</div>

## 预览

- [zhaoo's Blog](https://www.izhaoo.com)
- [卞卞不是便便](https://www.bianxr.com/)

（如果您正在使用 zhaoo 主题，欢迎展示您的博客哦，只需在 `README.md` 文件中加入您的博客，提交 PR 即可。）

## 特性

* 简约 & 响应式 & 动效
* 支持 `highlight` 代码高亮
* 支持 `Gitalk` 评论
* 支持 `FancyBox` 图片灯箱
* 支持 `Pjax` 无刷新加载
* 支持 `LeanCloud` 统计访问量
* 支持 `支付宝、微信` 打赏
* 支持格言，可配合插件 `hexo-plug-motto` 实现动态格言
* 支持定制 `主题风格`、`CDN`、`埋点脚本`、`社交链接`、`版权说明` 等

## 截图

![首页](./screenshots/home.png)

![文章页](./screenshots/article.png)

## 安装

安装 Hexo 后进入根目录：

```bash
$ cd hexo
```

安装 zhaoo 主题：

```bash
$ git clone https://github.com/izhaoo/hexo-theme-zhaoo.git themes/zhaoo
```

## 使用

修改 Hexo 根目录下的 `_config.yml` 文件启用 zhaoo 主题：

```yml
theme: zhaoo
```

建议将文章数量改为**9**篇，启用代码高亮效果：

```yml
index_generator:
  path: ''
  per_page: 9
  order_by: -date

highlight:
  enable: true
  line_number: true
  auto_detect: true
  hljs: true
  tab_replace:
```

启动 Hexo 服务器预览：

```bash
$ hexo clean && hexo s
```

## 配置

修改主题目录下的 `_config.yml` 文件，配置相关功能：

建议参考 [_config.yml](https://github.com/izhaoo/hexo-theme-zhaoo/blob/master/_config.yml) 进行配置

## 更新

移动到 zhaoo 主题目录：

```bash
$ cd themes/zhaoo
```

从 GitHub 获取更新：

```bash
$ git pull
```

## 协议

[MIT](https://github.com/izhaoo/hexo-theme-zhaoo/blob/master/LICENSE) License