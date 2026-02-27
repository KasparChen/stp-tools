# MHXY Tools

这是一个简单的梦幻西游工具集合，包含：
- 跑商抓鬼计时器 (`/mhxy/timer`)
- 召唤兽模拟器 (`/mhxy/summoner`)

## 如何部署到 Vercel

### 方法一：使用 Vercel CLI (推荐)

1.  安装 Vercel CLI:
    ```bash
    npm i -g vercel
    ```
2.  在当前目录运行:
    ```bash
    vercel
    ```
    (一路按回车确认即可)

### 方法二：使用 GitHub

1.  将此文件夹推送到 GitHub 仓库。
2.  在 Vercel 控制台导入该仓库。

## 域名配置

部署完成后，在 Vercel 项目设置中添加自定义域名 `tools.stp-studio.xyz`。
然后根据提示在你的域名服务商处添加 CNAME 记录指向 Vercel。
