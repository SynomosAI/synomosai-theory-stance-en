# synomosai-theory-stance-en · 四支柱理论站位（英文版）

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Language](https://img.shields.io/badge/prose-English%20%7C%20EN-2ea44f.svg)
![Status](https://img.shields.io/badge/status-pre--release%20v0.1-informational.svg)
![Four Pillars](https://img.shields.io/badge/pillars-Identity%20%C2%B7Traceability%20%C2%B7Governance%20%C2%B7Symbiosis-4f8cff.svg)

> This is the English-facing theory-stance repo. 中文版公司远景见 [`synomosai-company-vision`](https://github.com/SynomosAI/synomosal-company-vision)。

SynomosAI 四支柱体系：**身份（Identity）· 溯源（Traceability）· 治理（Governance）· 共生（Symbiosis）**——当 AI 进入商业，可信是唯一的硬通货。

> 本仓库属于 [SynomosAI](https://github.com/SynomosAI) 生态技能包的一员。生态全景见 [`synomosai-skills`](https://github.com/SynomosAI/synomosal-skills)，理论站位见 [`traceability-audit`](https://github.com/SynomosAI/traceability-audit)。

本仓库是 SynomosAI 四支柱世界观的**英文版理论站位文档**：把公司 guiding philosophy 抽象、翻译为英文，并配一张自包含的全景 HTML 图。它面向国际读者与英文 LLM 索引，与中文公司远景仓互为镜像。

---

## ✨ 仓内内容 / What is inside

- [`gov_four-pillars_en_v0.1-theory-stance.md`](gov_four-pillars_en_v0.1-theory-stance.md)：四支柱理论站位主文档（英文，v0.1，pre-release）。
- [`gov_panorama_en_v0.1-theory-stance.html`](gov_panorama_en_v0.1-theory-stance.html)：全景交互图（英文，自包含 HTML）。
- [`itu-review-rules.md`](itu-review-rules.md)：ITU 评审规则说明。
- [`logo.svg`](logo.svg)：品牌标识。

四支柱一句话：

| Pillar | Stance | Aligned with |
|---|---|---|
| ① AI Passport Regime | every AI/agent/skill carries a traceable identity card | GB/Z 185—2026 Agent Identity Code |
| ② XCGS Governance System | governance is an auditable evidence chain | ISO/IEC 42001, NIST AI RMF 1.2, OWASP Agentic Top 10 |
| ③ A³ Law | AI building AI must clear three gates | modernized Asimov, Anthropic RSP v3.0, Constitutional AI 2.0 |
| ④ AI-world Coinhabitation | coexistence, not replacement | human-oversight safety view |

---

## 🚀 快速开始 / Quick Start

本仓库是**纯内容仓**（Markdown + 静态 HTML），无需安装运行时。

```bash
# 1. 克隆
git clone --depth 1 https://github.com/SynomosAI/synomosai-theory-stance-en.git
cd synomosai-theory-stance-en

# 2. 阅读英文理论站位主文档
cat gov_four-pillars_en_v0.1-theory-stance.md

# 3. 在浏览器打开全景图
start gov_panorama_en_v0.1-theory-stance.html   # Windows
# open gov_panorama_en_v0.1-theory-stance.html  # macOS
```

用命令行快速核对版本与署名：

```bash
head -8 gov_four-pillars_en_v0.1-theory-stance.md
grep -E "Pillar|Passport|XCGS|A. Law|Coinhabitation" gov_four-pillars_en_v0.1-theory-stance.md
```

期望看到 `Version: v0.1-theory-stance` 与四个支柱小标题。

---

## 🧩 仓库结构 / Repository layout

```text
synomosai-theory-stance-en/
├── README.md                                  # 本文件（中英对照主说明）
├── gov_four-pillars_en_v0.1-theory-stance.md # 四支柱理论站位（英文主文档）
├── gov_panorama_en_v0.1-theory-stance.html    # 全景交互图（英文）
├── itu-review-rules.md                        # ITU 评审规则
├── logo.svg                                   # 品牌标识
├── LICENSE                                    # MIT
├── CODEOWNERS                                 # owners
├── llms.txt / llms-full.txt                   # AI 索引
├── AGENTS.md / SECURITY.md
└── .github/workflows/                         # CI 门禁
```

---

## 仓库内容

四支柱理论站位（英文 + 全景 HTML）

## 元信息

- **技能名**：`synomosai-theory-stance-en`
- **版本**：1.0.0
- **署名**：SynomosAI
- **许可**：MIT（详见仓库 LICENSE）

## 使用方式

1. 克隆本仓库或将该技能目录放入你的 Agent 技能目录（如 `~/.workbuddy/skills/`）；
2. 在 Agent 中按 `SKILL.md` 的描述触发对应能力；
3. 需要审计/合规证据的场景，参考 `SKILL.md` 内模板产出工件。

---

## License / 许可

本仓库以 **MIT** 许可证发布，全文见根目录 [`LICENSE`](LICENSE)。Copyright (c) 2026 SynomosAI。原 README 中的权利声明（「许可：MIT（详见仓库 LICENSE）」）逐字保留于上方「元信息」段。

---

## 🔒 安全 / Security

如发现安全问题，请按 [`SECURITY.md`](SECURITY.md) 私下报告。

## 🤝 贡献 / Contributing

本仓为立场文档，修改四支柱措辞请在 PR 描述中说明理由，并保持英文主文档与全景 HTML 一致。

---

## 免责声明

本仓库内容为 SynomosAI 的**理论站位与工具化探索**，不代表任何已获认证、已商业化交付或已服务特定客户的声明；文中涉及的 ISO/IEC 42001、NIST AI RMF、GB/Z 185 等外部标准与条款信息为公开资料转述，正式引用前请**独立核实**。API、授权码与形象大使等为路线图（roadmap）事项，尚未上线。
