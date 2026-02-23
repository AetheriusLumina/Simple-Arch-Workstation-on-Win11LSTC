# 🚀 WSL + Arch 工作站极简搭建指南

## 为什么有这份指南？

官方文档太长，网上教程太碎。这份指南为你剔除所有冗长理论，主打**无脑复制粘贴**。跟着做，只需半小时，你就能在 Windows 11 上搭建出简易 Linux 开发环境。

## 怎么读？怎么做？

按顺序执行：从上往下依次进行，前一步是后一步的基础，切勿跳步。

无脑复制：认准灰底的代码块，直接复制到对应终端按下回车运行。

注意替换：代码块中带有 `#` 的文字是注释说明（无需运行）；遇到提示输入“密码”、“用户名”、“地址”等字眼，请灵活替换为你自己的实际信息。

## 流程速览

[**系统设置**](./WorkstationGuide.md#系统设置)：到控制面板开启 Windows 11 必要的虚拟化和 Linux 子系统功能。

[**安装 WSL （Win Terminal）**](./WorkstationGuide.md#安装-wsl-win-terminal)：使用 Windows 终端一键下载并部署 Arch Linux。

[**设置 WSL （WSL Terminal）**](./WorkstationGuide.md#设置-wsl-wsl-terminal)：配置清华源、同步时间与语言，并创建你的日常专属账号。

[**基于 SSH 设定客户端（WSL Terminal）**](./WorkstationGuide.md#基于-ssh-设定客户端wsl-terminal)：开启并配置 SSH 服务，打通环境的内外部连接。

[**基于 Git 的简易项目仓库构建（WSL Terminal）**](./WorkstationGuide.md#基于-git-的简易项目仓库构建wsl-terminal)：生成并绑定 GitHub 密钥，跑通代码的克隆、提交与推送全流程。





🙏 特别感谢 [@Cornfy](https://github.com/Cornfy) 老师为本指南的整理与完善提供的无私帮助与技术支持！
