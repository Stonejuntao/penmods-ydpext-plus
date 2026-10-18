# ydpExt Plus

有道词典笔 YDP02X 增强扩展包（蓝牙双耳机 / 小说阅读 / 耳机触控 / 开机自启）。

## 功能

| 扩展 | 命令 | 说明 |
|------|------|------|
| 蓝牙管理 | `#bluetooth` | 双耳机同时出声、自动回连 |
| 小说阅读 | `#novel` | 离线书架 + 在线搜索 |
| AI 聊天 | `#gpt` | DeepSeek API |
| 网页搜索 | `#textweb` | 搜索引擎 |
| 终端 | `#terminal` | root shell |
| AVRCP 桥 | - | 耳机按键控制播放/暂停 |
| 开机自启 | - | 重启不丢功能 |

## 安装

### 前置条件
- 词典笔已刷 PenMods 1.2.0
- 有 root 权限

### 步骤
1. 下载 `ydpext-plus-完整安装包.zip`
2. 解压后双击 `install.cmd`
3. 选 SSH 或 ADB 安装，等跑完重启

## 配置

安装后编辑 `/userdisk/cookie/gpt_api_key.txt` 填入 DeepSeek API Key。

## 打赏

如果这个项目帮到了你，欢迎请我喝杯奶茶 ☕

![微信打赏](pay.png)
