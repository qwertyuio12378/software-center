# 软件坞 SoftDock

只收录官方下载源的软件下载中心。QXNET 2.1.5 覆盖安卓、苹果与 OS 三个平台，安装包暂未上架；另有 5 款 Windows 开发工具、5 条官方直链，全部经过真实请求与文件头校验。

- 在线访问：https://qwertyuio12378.github.io/software-center/
- 收录：QXNET 2.1.5（安卓 / 苹果 / OS）、VS Code、Python、Node.js、Git、Notepad++（Windows）
- 平台：Windows 5 款 / 安卓 1 款 / 苹果 1 款 / OS 1 款
- QXNET 安装包暂未上架，页面展示版本与三平台信息，下载按钮显示「安装包准备中」
- 站点为单文件 HTML，不依赖构建工具；GitHub Releases 的最新版追踪为按需请求

## 说明

本仓库只托管站点源码，不分发任何安装包。所有已上架工具的下载按钮均跳转到软件厂商自己的服务器（或厂商官方 GitHub Releases）。每条已上架链接的 HTTP 状态、Content-Type、字节数与文件头校验结果都记录在站点的详情抽屉中。

## 本地预览

```bash
python3 -m http.server 8080
```

然后打开 http://localhost:8080/ 。
