# Blog

基于 [Zensical](https://zensical.org/) 搭建的个人博客，部署在 [GitHub Pages](https://tomtc123.github.io/blog/)。

## 本地开发

```bash
# 安装依赖
uv add --dev zensical

# 启动本地开发服务器（支持热重载）
zensical serve

# 构建静态站点
zensical build --clean
```

## 项目结构

```
docs/
  index.md                -- 首页
  markdown.md             -- Markdown 语法速查
  build-blog/             -- 博文：使用 Zensical 搭建博客
zensical.toml             -- 站点配置
.github/workflows/docs.yml -- GitHub Actions 自动部署
```

## 部署

推送到 `main` 分支后，GitHub Actions 会自动构建并部署到 GitHub Pages。
