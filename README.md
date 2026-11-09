# JoyeaBridge 远程 AI 协同

这是公开下载仓库，只提供安装包和使用说明。开发源码保存在私有仓库。

**[点击下载最新安装包和完整包](https://github.com/wangxinhaoreal-debug/JoyeaBridge-Downloads/releases/latest)**，不需要登录 GitHub。

- 新现场端：下载 `JoyeaBridge-Public-Complete-0.2.1.zip`，完整解压，安装配套 DSH 和 JoyeaBridge。
- 新使用端：只需 `JoyeaBridge-Public-Setup-0.2.1.exe`。
- 从部署管理员获取新的接入码，打开软件粘贴并连接，不需要手填端口。
- 管理员通过软件“管理接入码”入口登录生成接入码。下载包不含管理员账号或接入码。
- 使用端连接后，选中服务，点“接入其他 AI”复制配置与说明给本机 AI。

现场 DSH 版本为 0.2.1-rc.5；安装器内置 Node。已有其他版本 DSH 时请先备份并确认后再更换。JoyeaBridge 安装器未签名，SHA256SUMS.txt 提供校验值。本版没有自动更新功能。

公开版使用独立安装目录与状态目录。0.2.1 支持迁移配套旧版 0.1.5 身份，保留原始文件，不需要重新登记。安装前需正常退出 Bridge，不会强行停止任务或 RustDesk。

0.2.1 支持同一台电脑同时连接远端 AI 和提供本机 DSH。已有 0.2.0 用户下载 Upgrade 升级包，正常退出 Bridge 后安装，身份和授权保留；安装时短暂断线，启动后重连。无需卸载或换已有接入码。

后续更新：点软件底部“检查更新 / 下载升级包”，下载 Upgrade 包，全部解压后双击“01-一键升级.cmd”。它校验安装器并自动安装；仍在运行的 Bridge 会阻止升级并提示先退出。
