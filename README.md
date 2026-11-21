# 弱网坞 WeakDock

只收录官方下载源的软件下载中心。QXNET 2.1.5 覆盖安卓、苹果与鸿蒙三个平台，安装包暂未上架；另有 5 款 Windows 开发工具、5 条官方直链，全部经过真实请求与文件头校验。

- 在线访问：https://qxnetz.ccwu.cc/
- 备用地址：https://qwertyuio12378.github.io/software-center/
- 收录：QXNET 2.1.5（安卓 / 苹果 / 鸿蒙）、VS Code、Python、Node.js、Git、Notepad++（Windows）
- 平台：Windows 5 款 / 安卓 1 款 / 苹果 1 款 / 鸿蒙 1 款
- QXNET 安装包暂未上架，页面展示版本、三平台信息与文件格式（APK / IPA / HAP），下载按钮显示「安装包准备中」
- 站点为两个自包含 HTML（前台 `index.html`、后台 `admin.html`），不依赖构建工具；GitHub Releases 的最新版追踪为按需请求

## 后台管理

- 地址：`/admin.html`
- 支持新增、编辑、排序、删除分类；新增、编辑、删除应用
- 应用可配置名称、分类、英文名、官网、简介、标签、主题色、图标，以及 Windows / 安卓 / 苹果 / 鸿蒙各平台的版本、格式、体积、文件名、官方直链、来源、上架状态、HTTP 状态与 Content-Type
- 数据保存在同一域名下当前浏览器的 `localStorage`（key：`weakdock_admin_v1`），前台读取同一份数据
- 后台提供「导出 JSON / 导入 JSON」，用于备份或迁移到另一台设备

## 说明

本仓库只托管站点源码，不分发任何安装包。所有已上架工具的下载按钮均跳转到软件厂商自己的服务器（或厂商官方 GitHub Releases）。每条已上架链接的 HTTP 状态、Content-Type、字节数与文件头校验结果都记录在站点的详情抽屉中。

## 本地预览

```bash
python3 -m http.server 8080
```

然后打开 http://localhost:8080/ 。
