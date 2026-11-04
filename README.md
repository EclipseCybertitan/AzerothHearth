# Azeroth Hearth / 公会炉石

公会职业登记、公报和界面制式放在一起。全文在插件里看，聊天提醒由作者手动发送。

Guild RP registrations, bulletins and shared layouts in one addon. Read the full bulletin in the addon; chat notices are sent manually by the author.

**[下载 / Download 1.2.3](https://github.com/EclipseCybertitan/AzerothHearth/releases/tag/v1.2.3)** · [所有版本 / All releases](https://github.com/EclipseCybertitan/AzerothHearth/releases)

## 安装与更新

下载 Release Assets 中的 `-forever.zip`，退出游戏、备份旧版后，把 `AzerothHearth` 文件夹放进正确客户端的 `Interface/AddOns`。不要下载 **Source code**，那是指南仓库快照，不能安装。

WowUp → **Get Addons → Install from URL**，填写：

`https://github.com/EclipseCybertitan/AzerothHearth`

回滚前关闭 **Auto Update** 并开启 **Ignore**。GitHub 不通时，可通过公会可信渠道转交原 ZIP 和校验文件，手动更新。

[中文安装与回滚说明](安装升级与回滚.txt) · [发布维护](发布维护指南.txt) · [开发者的话](开发者与时间线.txt)

## Install and update

Download the `-forever.zip` asset. Exit the game, back up, and place its `AzerothHearth` folder in the correct client's `Interface/AddOns`. **Source code** downloads are guide snapshots, not installable addons.

In WowUp, use **Get Addons → Install from URL** with the repository URL above. Turn off **Auto Update** and enable **Ignore** before a rollback. If GitHub is unreachable, use an unchanged ZIP and checksum passed through a trusted guild file channel.

[English installation guide](INSTALL.en.txt) · [About the designer](ABOUT.en.txt)

## 兼容范围 / Compatibility

目标是国服“无限” Interface 16001。目前界面是中文。离线测试已完成，真实 WowUp 安装、Windows/macOS 游戏运行和成员网络仍待验证。职业领袖怎么选，由公会决定。

Target: China-region WoW: Forever (无限), Interface 16001. The UI is currently in Chinese. Offline tests have passed; actual WowUp installation, Windows/macOS game operation and member networks remain unverified. Election rules are up to the guild.

The designer plays on the China-region servers.

这里只公开安装包和说明，完整开发历史及独立源码包留在本机。This repository publishes installers and documentation only; development history and standalone source packages remain local. The Lua files inside an installer are required to run the addon.

© 2026 **Mart，艾泽拉斯人类大法师** / **Mart, Human Archmage of Azeroth**. 免费 / Free. MIT license.
