# 标准、框架与行业实践映射

> 核对基准日期：2026-10-27。正式采用前，应重新核验官方页面上的最新版本、修订状态和适用性。

## 1. 分类规则

- **A — 官方发布文件**：标准、框架或指南已正式发布。此标记不代表对所有组织有法律强制力。
- **B — 行业实践**：行业安全组织、专业社区或工程指南中的建议。
- **C — 本方案建议**：本仓库设计的控制、指标、测试阈值和流程。

## 2. 参考文件

| 文件 | 分类 | 本方案用途 | 说明 |
|---|---|---|---|
| NIST AI RMF 1.0 | A | AI 风险治理、识别、测量、管理 | 自愿性风险管理框架；NIST 已推进修订工作 |
| NIST AI 600-1, Generative AI Profile | A | 生成式 AI 特有风险管理 | 用于补充通用 AI 风险流程 |
| NIST Cybersecurity Framework 2.0 | A | 网络安全治理、识别、防护、检测、响应、恢复 | 通用网络安全框架 |
| NIST SP 800-53 Rev. 5.2.0 | A | 访问控制、审计、配置、事件响应、隐私等控制参考 | 应根据组织与系统环境选取控制，不应盲目全量套用 |
| NIST SP 800-207, Zero Trust Architecture | A | 身份、资源和会话级访问控制 | 支持零信任架构设计 |
| OWASP GenAI / LLM Top 10 2026 | B | 大模型应用攻击面与测试场景 | 行业风险指南，不是政府法规 |
| OWASP RAG Security Cheat Sheet | B | RAG 导入、检索、权限元数据、隔离和输出风险 | 工程实践参考 |
| 本仓库控制矩阵和测试阈值 | C | 企业实施、验收与审计 | 企业自定义基线，需按风险调整 |

## 3. 官方来源

1. NIST AI Risk Management Framework  
   https://www.nist.gov/itl/ai-risk-management-framework

2. NIST AI 600-1: Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile  
   https://doi.org/10.6028/NIST.AI.600-1

3. NIST Cybersecurity Framework  
   https://www.nist.gov/cyberframework

4. NIST SP 800-53 Rev. 5, Security and Privacy Controls for Information Systems and Organizations  
   https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final

5. NIST SP 800-207, Zero Trust Architecture  
   https://doi.org/10.6028/NIST.SP.800-207

6. OWASP GenAI Security Project — OWASP Top 10 for LLM Applications 2026  
   https://genai.owasp.org/resource/owasp-genai-llm-top-10-2026/

7. OWASP RAG Security Cheat Sheet  
   https://cheatsheetseries.owasp.org/cheatsheets/RAG_Security_Cheat_Sheet.html

8. NIST AI Agent Standards Initiative（用于跟踪 Agent 标准化进展，不应视为已完成的统一认证标准）  
   https://www.nist.gov/news-events/news/2026/02/announcing-ai-agent-standards-initiative-interoperable-and-secure

## 4. 控制映射原则

- NIST 文件用于建立治理、控制目标和风险管理过程。
- OWASP 文件用于补充应用层威胁、攻击场景和工程防御措施。
- 企业内部阈值、SLA、责任分工和上线门禁属于本地治理决定。
- 如客户合同、行业监管或法律提出更严格要求，应优先满足适用的强制要求。
- 不得仅因“参考 NIST”或“参考 OWASP”就宣称获得认证或保证绝对安全。
