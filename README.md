# My Blog

这是一个使用 Hugo 构建的个人博客项目。

## 项目结构

- **content/**: 博客文章目录（子仓库）
- **public/**: 生成的静态网站文件（子仓库，部署到 GitHub Pages）
- **themes/Hugo-Octopress/**: 博客主题（子仓库）

## 克隆仓库和子模块

使用以下命令克隆主仓库和所有子模块：

```bash
git clone --recursive git@github.com:Military-axe/blog.git
```

如果已经克隆了主仓库但没有初始化子模块，可以使用以下命令：

```bash
git submodule init
git submodule update
```

## 构建博客

1. 安装 Hugo（如果尚未安装）
2. 在项目根目录执行以下命令生成静态网站：

```bash
hugo
```

生成的静态文件将存储在 `public/` 目录中。

## 部署

静态网站文件将自动部署到 GitHub Pages，仓库地址为：
- **Repository**: git@github.com:Military-axe/Military-axe.github.io.git
- **URL**: https://military-axe.github.io/

## 子仓库信息

- **内容仓库**: git@github.com:Military-axe/blog_markdown.git
- **主题仓库**: https://github.com/parsiya/Hugo-Octopress
- **部署仓库**: git@github.com:Military-axe/Military-axe.github.io.git