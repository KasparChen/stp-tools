# STP Tools

这是一个包含梦幻西游工具集的简单静态网站项目。

## 工具列表

- **Timer (计时器)**: `/timer` (对应文件: `mhxy/timer.html`)
- **Simulator (模拟器)**: `/simulator` (对应文件: `mhxy/simulator.html`)

## 部署说明

本项目配置为使用 Vercel 部署。

### 目录结构

- `mhxy/`: 包含具体的工具 HTML 文件。
- `vercel.json`: Vercel 的路由配置文件，用于将 `/timer` 映射到具体文件。
- `index.html`: 简单的导航主页。

### 如何更新

1. 修改 `mhxy/` 下的 HTML 文件。
2. 提交代码到 GitHub。
3. Vercel 会自动重新部署。
