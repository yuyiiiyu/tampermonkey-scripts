# 抖音精简优化 + 下载（Chrome 版）

> 油猴（Tampermonkey）用户脚本 · 适用浏览器：**Google Chrome**

| 项目 | 说明 |
| --- | --- |
| 脚本名 | 抖音精简优化 + 下载 |
| 作者 | nnn U |
| 版本 | 1.0.20 |
| 许可 | MIT |
| 生效站点 | `douyin.com`、`iesdouyin.com` |
| 脚本文件 | `抖音精简优化+下载.user.js` |

## 一键安装

1. 在 Chrome 中安装 [Tampermonkey](https://www.tampermonkey.net/) 扩展；
2. 打开下面的 Raw 链接，Tampermonkey 会自动识别并弹出安装界面，点击「安装」即可：

   `https://raw.githubusercontent.com/yuyiiiyu/tampermonkey-scripts/main/油猴脚本/抖音/chrome/抖音精简优化+下载.user.js`

## 简介

**一：精简优化**

- 去掉播放器底部黑色遮罩；
- 让控制条常亮；
- 全屏时不裁剪画面；
- 自动切到最高画质；
- 打开首页默认进「推荐」。

**二：下载**

- 支持视频、图集、封面、弹幕下载，支持调用外部下载器。

## 下载功能

视频、图集、封面、弹幕 ass 文件下载。支持浏览器直接下载。作者主页批量下载可选开启。下载历史记录。
快捷键默认按 **M** 下载当前视频，可在设置中修改。

## 已知问题

若在桌面建立抖音网页版的快捷方式，则电脑刚开机后的第一次打开桌面的抖音快捷方式，脚本可能会不运行。

## 解决办法

- **法一**：刷新一下即可（直至下次开机之前都可以稳定运行，非永久）；
- **法二**：浏览器打开而非直接桌面快捷方式打开；
- **法三（永久解决）**：
  1. `chrome://extensions/` → 找到 Tampermonkey 卡片 → 打开「允许用户脚本」；
  2. 油猴面板 → 设置 → 配置模式改成 **高级（Advanced）** → 把「Content Script API」一项改成 **UserScripts API Dynamic** → 保存。

## 有问题？

欢迎到仓库 Issues 反馈：https://github.com/yuyiiiyu/tampermonkey-scripts/issues
