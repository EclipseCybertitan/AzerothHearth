# 公会炉石 · Azeroth Hearth

© 2026 **Mart，艾泽拉斯人类大法师**。免费，MIT 许可。目标国服《魔兽世界：无限》Interface **16001**；实机兼容性未验收。

本仓库只公开 **安装包和中文指南**。开发源码仓库、完整 Git 历史、独立源码包、测试与构建工具不在此公开。安装 ZIP 中的 Lua 是插件运行必需文件。

## 下载和订阅更新

- [发行与下载目录](https://github.com/EclipseCybertitan/AzerothHearth/releases)
- [安装、升级、回滚和国内网络备用指南](安装升级与回滚.txt)
- WowUp → Get Addons → Install from URL，粘贴：`https://github.com/EclipseCybertitan/AzerothHearth`
- 下载 Release **Assets** 中的 `AzerothHearth-版本-forever.zip` 和同名 `.sha256`。不要下载 GitHub 自动显示的 **Source code**；在这个仅分发仓库中，它只是指南快照，不是插件安装包。
- 各版附件以发行页实际列出的内容为准；旧版保留供回滚。

## 成员安装

完全退出游戏，备份旧插件与本角色 SavedVariables。核对 ZIP 的 SHA-256，将旧 `AzerothHearth` 目录完整移到 AddOns 之外，再把新 ZIP 内的同名文件夹放入正确客户端的 `Interface/AddOns`。最终路径为 `Interface/AddOns/AzerothHearth/AzerothHearth.toc`，不能多套一层。

首次由 1–2 名成员完成实机核验，再扩大到 10 人。安装后 `/ah diagnose` 查看本机版本，`/ah versions` 仅辅助核对其他成员自报版本，不能代替安装或文件完整性验收。

## 升级与回滚

WowUp 可检查此仓库的 Release。成员自行选择是否开启 Auto Update；自动检查不是即时推送，管理器关闭或网络不可达时不能保证更新。回滚前必须关闭 Auto Update 并勾选 Ignore，再退出游戏、备份、完整安装旧版。不要删除全部 WTF 或覆盖其他插件。

1.2.1 与 1.2.0 保持 schema 2、AHCOMM2；1.1.0 可以收全文和撤稿，但不支持新回执与版本查询。回执不是已读。回退更早版本需使用配套存档，不能修改 schema 数字。

国内无法访问 GitHub 时，由维护者通过公会既有可信文件渠道转交原 ZIP、校验文件和指南，成员手动更新。不要解压重打包或索取作者令牌；不需要开放电脑入站端口、路由器端口映射或关闭防火墙。

## 发布边界

此公开仓库不部署源码构建工作流。维护者在本地构建并验证完整安装包，再发布 Release；WowUp 从这里检查更新。Release 标签标识分发记录，不是独立开发源码提交。仅选择普通 ZIP URL 安装不能订阅后续更新。

本项目未打开、读取或复制游戏；已完成的本地模拟、ZIP 验证不等于在 WowUp 桌面程序安装成功或 Win/Mac 游戏实机通过。职业领袖与选举规则仍待负责人设计，公会和人物示例均为占位。

依据：[WowUp URL 安装说明](https://wowup.io/guide/get-addons/overview)、[更新与 Ignore 说明](https://wowup.io/guide/my-addons/addons)。


[来自另一条时间之流：开发者来信](开发者与时间线.txt)

