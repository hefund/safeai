# 发布到 GitHub

## 发布前检查
- [ ] 核对 `docs/STANDARDS_MAPPING.md` 中官方链接与当前版本。
- [ ] 确认没有真实公司名称、客户资料、内部 IP、密钥或敏感信息。
- [ ] 按自身企业环境调整验收阈值与 SLA。
- [ ] 填写 `SECURITY.md` 中私密漏洞报告渠道。
- [ ] 确认许可证适合你的发布目的。
- [ ] 由安全/法务人员审核是否适合公开发布。

## 新建 GitHub 仓库并推送
在 GitHub 上创建一个空仓库，然后在本目录运行：

```bash
git init
git add .
git commit -m "Initial enterprise AI security baseline"
git branch -M main
git remote add origin https://github.com/<OWNER>/<REPOSITORY>.git
git push -u origin main
```

将 `<OWNER>` 和 `<REPOSITORY>` 替换为实际仓库所有者和仓库名。

## 建议仓库简介
Chinese enterprise security baseline for internal AI platforms and RAG knowledge bases, with controls, acceptance criteria, test cases, governance, and NIST/OWASP mapping.

## 建议 GitHub Topics
`ai-security`, `llm-security`, `rag-security`, `nist-ai-rmf`, `owasp`, `enterprise-ai`, `security-baseline`
