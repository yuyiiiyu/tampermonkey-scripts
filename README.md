# 🧩 油猴脚本仓库（Tampermonkey Userscripts）

> 本仓库用于集中存放 **油猴（Tampermonkey / 用户脚本）** 脚本，按 **「站点或功能 / 浏览器」** 两级分类管理。
> 每个脚本目录下都有 `.user.js` 脚本本体 + 一份 `README.md` 使用说明，Raw 链接可直接点开安装。

## 📦 如何安装脚本

1. 浏览器安装 [Tampermonkey](https://www.tampermonkey.net/) 扩展（Chrome / Edge / Firefox 均可）；
2. 在下表中点开对应脚本的 **Raw 安装链接**；
3. Tampermonkey 会自动识别脚本，点击「安装」即可。

## 🗂 脚本目录

| 脚本 | 分类（站点/功能） | 浏览器 | 版本 | 说明文档 |
| --- | --- | --- | --- | --- |
| [抖音精简优化 + 下载](https://github.com/yuyiiyu/tampermonkey-scripts/tree/main/scripts/douyin/chrome) | `douyin` | Chrome | 1.0.20 | [README](scripts/douyin/chrome/README.md) |
| [抖音精简优化 + 下载](https://github.com/yuyiiyu/tampermonkey-scripts/tree/main/scripts/douyin/edge) | `douyin` | Edge | 1.0.6 | [README](scripts/douyin/edge/README.md) |

## 📁 仓库结构

```
scripts/
└── douyin/                          # 分类：按站点或功能命名（如 douyin / bilibili / weibo …）
    ├── chrome/                      # 浏览器：Chrome 版
    │   ├── 抖音精简优化+下载.user.js
    │   └── README.md
    └── edge/                        # 浏览器：Edge 版
        ├── 抖音精简优化+下载.user.js
        └── README.md
```

## ➕ 以后怎么新增脚本

1. 在 `scripts/` 下按功能/站点新建一个分类目录（例如 `scripts/bilibili/`）；
2. 在分类目录里按浏览器建子目录（`chrome/`、`edge/` …）；
3. 放入 `xxx.user.js`（文件名必须以 `.user.js` 结尾，这样 Raw 链接点开就能一键安装）与 `README.md` 说明（建议包含：作者、版本、许可、功能、快捷键、已知问题、解决办法）；
4. 回到本文件，在「脚本目录」表格里补一行。

## 📄 许可

脚本均为 **MIT** 许可，作者 nnn U。使用请遵守各站点的服务条款，下载内容仅个人学习交流使用。
