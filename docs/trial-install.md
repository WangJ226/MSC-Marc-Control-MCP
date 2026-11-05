# 安装与首次使用

1. 在 [Releases](https://github.com/WangJ226/MSC-Marc-Control-MCP/releases) 查看可用 EXE、校验文件与版本说明。当前列表为空时，联系提供方安排体验包。GitHub 的 Source code 归档是公开资料。
2. 事先准备已授权 Marc/Mentat 和已登录的 WorkBuddy、Codex 或 Claude Desktop。安装包携带 MCP 自身 Python 运行环境。
3. 安装软件，输入提供方发放的邮箱与激活码，或按界面兑换入口输入兑换码。授权期限以界面显示为准；体验申请人工批准。
4. 点击自动查找 Marc，多个安装时选择目标版本，再执行环境检查。组织许可证信息向所在单位确认。
5. 选择 AI 客户端完成配置，重载客户端并确认信任；配置成功后继续验证实际工具调用。
6. 发送 [首次检查提示](codex-setup-prompt.md)，先执行只读检查。用一个项目副本测试；修改模型、启动 Mentat 和求解前确认具体操作。
7. 核对状态、目标文件及实际输出。出现问题时导出诊断 JSON，检查脱敏后反馈。

升级前关闭相关 AI 连接，选择原安装目录保留设置。重装或换机请联系提供方核对授权。

## English
Install the supplied EXE, activate with the issued code, detect Marc and run the environment check. Configure your AI client, reload it and confirm trust. Call `run_mcp_doctor` before a small task on a project copy. Approve model changes and execution individually. The installer bundles the MCP Python runtime; bring your licensed Marc installation and AI account. Review and sanitize diagnostics before sharing.

[日本語の導入手順](trial-ja.md) · [返回介绍](../README.zh-CN.md)
