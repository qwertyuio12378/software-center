# 软件坞 SoftDock

只收录官方下载源的开发工具下载中心。5 款开发工具、5 条官方直链，全部经过真实请求与文件头校验。

- 在线访问：https://qwertyuio12378.github.io/software-center/
- 收录：VS Code、Python、Node.js、Git、Notepad++
- 平台：Windows 5 款
- 站点为单文件 HTML，不依赖构建工具；GitHub Releases 的最新版追踪为按需请求

## 说明

本仓库只托管站点源码，不分发任何安装包。所有下载按钮均跳转到软件厂商自己的服务器（或厂商官方 GitHub Releases）。每条链接的 HTTP 状态、Content-Type、字节数与文件头校验结果都记录在站点的详情抽屉中。

## 本地预览

```bash
python3 -m http.server 8080
```

然后打开 http://localhost:8080/ 。
