# 来源与归属说明

## TrendRadar

StockPilot AI 的资讯采集、热点聚合与部分自动化能力基于开源项目 [sansan0/TrendRadar](https://github.com/sansan0/TrendRadar) 的思路与代码基础进行扩展和整合。

TrendRadar 上游仓库采用 GPL-3.0 许可证。若后续在本仓库中直接分发来自 TrendRadar 的源代码或其衍生代码，应继续遵守对应许可证要求，并保留上游版权与许可说明。

本作品集仓库当前主要公开：

- 产品设计文档；
- 架构说明；
- 脱敏后的工作流结构示例；
- Prompt 示例；
- Schema 示例；
- 失败案例与可靠性设计。

并不把生产环境中的完整 TrendRadar 代码复制到本仓库。

## AShare MCP

A 股工具层来自用户维护的独立仓库：

- https://github.com/chenyutong0702/ashare-mcp

StockPilot 通过 MCP / Tool Calling 使用其中的行情、K 线、技术分析、资金流等能力。

## 公开版与生产版差异

本仓库是求职与产品作品集用途的公开版。为避免泄露真实运行环境，以下信息不会公开：

- API Key / Token；
- Supabase Service Role Key；
- Backblaze B2 Application Key；
- 微信 Bridge Token；
- Dify 私有数据集 ID；
- 私有服务地址；
- 真实自选股、成本价与个人 Investment Thesis；
- 私人聊天记录。
