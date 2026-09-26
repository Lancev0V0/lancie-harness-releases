# Lancie Harness

Windows 桌面助手的安装包与更新发布仓库。

**[下载 Windows x64 最新版](../../releases/latest)**

## 安装与更新

下载安装包并运行，按提示完成安装。目标系统为 Windows 10 22H2 / Windows 11 x64；安装包包含 Codex 引擎与 WebView2 离线运行组件，不需要另装 Node、Python、Rust。

0.3.1 起内置本仓库更新地址。软件启动时检查新版，在“设置 → 通用 → 软件更新”中下载并选择安装时间。更新会关闭并重新打开软件；正在执行任务时不能安装。

## 使用说明

本地模式需要你自己的 Codex 登录和可用的模型服务网络。可在设置中选用其他 API 服务协作；相关调用使用你自己的服务额度。首次使用说明和模型价格参考在软件“帮助”中。

程序使用官方 Codex 引擎，但 Lancie Harness 是独立客户端，不是 OpenAI 官方桌面应用，也尚未实现其全部功能。当前为内测版。

## 校验与已知边界

- 更新器验证安装包签名及对应版本；`.sig` 是更新签名。
- 尚无 Windows Authenticode 发布者证书，Windows 可能显示未知发布者。
- 本机原生 Windows 更新链路已验证；不同电脑环境及普通国内网络仍需实际验证。
- 本仓库只分发安装包和更新清单，不包含用户登录、API Key、项目材料、聊天记录或更新签名私钥。
- 第三方许可随安装包提供。

固定更新清单：<https://github.com/Lancev0V0/lancie-harness-releases/releases/latest/download/latest.json>
