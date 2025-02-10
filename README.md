# 文档 [![Discord](https://img.shields.io/discord/289587909051416579.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/papermc)![部署状态](https://img.shields.io/github/deployments/PaperMC/docs/production?label=部署&logo=github)![许可证](https://img.shields.io/github/license/PaperMC/docs)

这是 PaperMC 旗下所有项目文档的代码仓库。此仓库中的内容会发布到 [docs.papermc.io](https://docs.papermc.io) 以供查看。

## 入门指南

如何在本地机器上运行文档以便进行开发。

### 前提条件
- [node](https://nodejs.org)
- [pnpm](https://pnpm.io/installation)

### 本地开发
1. 克隆代码仓库。如果你打算进行修改，先创建一个复刻版！
```bash
$ git clone https://github.com/PaperMC/docs
```
2. 安装所有必需的依赖项。
```bash
$ pnpm install
```
3. 启动开发服务器。
```bash
$ pnpm run dev
```
这将启动一个本地开发服务器并打开一个浏览器窗口。大多数更改会立即实时反映出来，无需重新启动开发服务器或在浏览器中重新加载页面。尽情编辑吧！

### 构建
```bash
$ pnpm run build
```
此命令会在 `build` 目录中构建一个适用于生产环境的部署版本。这些文件可直接托管在任何静态内容服务器上。

## 许可证
PaperMC 文档（例如 `/docs` 文件夹中的 `.md` 文件）采用 [CC - BY - SA - 4.0](https://github.com/PaperMC/docs/blob/main/LICENSE-docs) 许可证。

支持代码采用 [BSD - 2 - 条款](https://github.com/PaperMC/docs/blob/main/LICENSE) 许可证。

PaperMC 标志受其 [自身条款](https://docs.papermc.io/misc/assets) 约束，并不继承它所代表的任何项目的许可证。
