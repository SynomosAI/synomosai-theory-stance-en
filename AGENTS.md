# AGENTS.md — 给 AI Agent 的工作指引

本文件面向自动化 AI Agent。人类读者请看 [README.md](README.md)。

## 这个仓库是什么

`synomosai-theory-stance-en` 是一个**纯内容仓**（英文版理论站位），不是可运行的 SDK。核心资产是英文 Markdown `gov_four-pillars_en_v0.1-theory-stance.md` 与全景 HTML `gov_panorama_en_v0.1-theory-stance.html`。它把公司 guiding philosophy 抽象、翻译为英文，面向国际读者与英文 LLM 索引。

## 可用的工作命令

```bash
# 查看主文档版本与署名
head -8 gov_four-pillars_en_v0.1-theory-stance.md

# 列出四支柱小节
grep -E "Pillar|Passport|XCGS|Coinhabitation" gov_four-pillars_en_v0.1-theory-stance.md
```

前置依赖：无；只需一个能打开 HTML 的浏览器。

## 约定（Do）

- 修改四支柱英文措辞时，保持与中文公司远景仓（`synomosai-company-vision`）语义一致。
- 新增内容须标注来源（源文件 / 版本），不引入源材料之外的新主张。
- 修改后主文档与全景 HTML 保持同步。

## 禁止（Don't）

- 不要改动 `LICENSE` 的版权主体（Copyright (c) 2026 SynomosAI）与许可口径——**权属字段只由维护者变更**。
- 不要在仓内提交任何密钥、令牌或真实客户数据。
- 不要声称本仓「已认证 / 已商用交付 / 已服务特定客户」。
- 不要把本仓当作可执行检查器。

## 边界

本仓专注**英文版理论站位陈述**；不覆盖具体合规检查、审计流程。需要可运行检查时指向生态内工具仓。
