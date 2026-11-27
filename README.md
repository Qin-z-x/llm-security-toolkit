# LLM 安全防护 7 件套

真实可用、证据可复现的开源防护工具，覆盖 LLM 应用常见 7 类攻击面。

| 工具 | 说明 | B站演示 |
|---|---|---|
| [llm-markdown-xss-guard](https://github.com/Qin-Z-x/llm-markdown-xss-guard) | 模型输出 XSS 净化：渲染进网页的模型输出可能带脚本/事件处理器 | [60 秒](https://www.bilibili.com/video/BV1BE1pztEmt) |
| [tool-call-arg-guard](https://github.com/Qin-Z-x/tool-call-arg-guard) | 工具调用参数注入校验：模型生成的工具参数可能带命令拼接/路径穿越/SSRF | [60 秒](https://www.bilibili.com/video/BV1BE1pztEYA) |
| [model-pii-redactor](https://github.com/Qin-Z-x/model-pii-redactor) | 输出 PII/密钥脱敏：模型输出会泄露邮箱/卡号/API key | [60 秒](https://www.bilibili.com/video/BV1fE1pztE53) |
| [rag-poison-guard](https://github.com/Qin-Z-x/rag-poison-guard) | RAG 语料投毒扫描：检索文档可能藏注入指令与隐藏内容 | [60 秒](https://www.bilibili.com/video/BV1BE1pztE4o) |
| [llm-sql-injection-guard](https://github.com/Qin-Z-x/llm-sql-injection-guard) | 生成 SQL 注入 lint：模型写的 SQL 可能拼接/恒真/UNION 注入 | [60 秒](https://www.bilibili.com/video/BV1BE1pztEME) |
| [ai-agent-permission-guard](https://github.com/Qin-Z-x/ai-agent-permission-guard) | Agent 权限审计：工具清单权限过大：shell/写盘/网络/密钥 | [60 秒](https://www.bilibili.com/video/BV1fj1pzfE2W) |
| [llm-file-path-guard](https://github.com/Qin-Z-x/llm-file-path-guard) | 路径穿越扫描：生成代码可能写敏感路径/../穿越 | [60 秒](https://www.bilibili.com/video/BV1761HzsEWJ) |

- 在线页：https://qin-z-x.github.io/llm-security-toolkit/
- B站合集（4 分钟）：https://www.bilibili.com/video/BV1jH1pz4ED7

诚实边界：启发式检测；每项目 THREAT_MODEL/EVIDENCE 有可复现证据。MIT License.
