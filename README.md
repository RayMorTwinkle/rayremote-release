# RayRemote 被控端下载

RayRemote 是窗口级远程控制平台：浏览器 viewer 零安装，被控端常驻静默、不抢焦点。

本仓库**只发布安装包**，不含源码。

## 下载

| 平台 | 包 | 说明 |
|---|---|---|
| macOS | `RayRemote-<版本>.zip` | macOS 14+，解压后按指引拖入 /Applications |
| Windows | `RayRemote-windows-amd64.zip` | Windows 10+ x64 |

→ **[Releases 页面](https://github.com/RayMorTwinkle/rayremote-release/releases)**

GitHub 打不开？官网提供国内高速下载：**https://rr.raymondreal.dpdns.org/**

## 安装

### macOS

解压 zip，将 `RayRemote.app` 拖入「应用程序」后打开，按 app 内指引完成授权即可。

### Windows

解压 zip 后在包目录运行：

```powershell
powershell -ExecutionPolicy Bypass -File install.ps1 -Server wss://rr.raymondreal.dpdns.org/ws -Http https://rr.raymondreal.dpdns.org -Start
```

即完成安装与开机自启。未签名版本首次运行会弹 SmartScreen，选「仍要运行」即可。

## 绑定

安装完成后打开控制面板，任选其一：

- **配对码**：面板生成配对码，在网页端控制台输入确认
- **账号登录**：面板里直接用云端账号登录并绑定

没有账号？先在网页端控制台注册。

## 控制台（网页端）

**https://rr.raymondreal.dpdns.org/app** — 注册 / 登录 / 绑定管理 / 远程控制都在浏览器里完成。
