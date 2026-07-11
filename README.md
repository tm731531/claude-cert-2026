# Anthropic Claude 認證備考 — CCAR-P（2026）

> Anthropic 官方 Claude 認證的個人備考整理。以 **CCAR-P（Certified Architect – Professional）** 為目標，資料來源為官方考綱 PDF 與 Pearson VUE。GitHub Pages 提供考綱速覽 + 互動自我測驗。

## 🎯 目標證：CCAR-P
- **全英文考試、禁用瀏覽器翻譯**
- 63 題 / 120 分鐘 / 及格 720（滿分 1000，criterion-referenced）
- 費用 $175 · 效期 12 個月 + 免費線上續證
- 每 12 個月最多重考 4 次（間隔 14 / 30 / 90 天）

## ✍️ 線上備考網站
👉 **https://tm731531.github.io/claude-cert-2026/**
- [考綱速覽](https://tm731531.github.io/claude-cert-2026/reference.html)：四張證對照 + CCAR-P 七大考域配分與細目 + 落差分析
- [自我測驗](https://tm731531.github.io/claude-cert-2026/quiz.html)：3 題官方 sample + 依考綱自製練習，打亂選項、即時對答、計分、錯題重練

## 📊 四張證一覽（Pearson VUE 官方）

| 代碼 | 名稱 | 對象 | 費用 | 題數/時間 |
|---|---|---|---|---|
| CCAO-F | Associate – Foundations | 商業/行銷/PM/教育 | $99 | 60 / 120′ |
| CCDV-F | Developer – Foundations | 軟體工程師 | $125 | 53 / 120′ |
| CCAR-F | Architect – Foundations | 技術專家/顧問 | $125 | 60 / 120′ |
| **CCAR-P** | **Architect – Professional** | 資深/企業級 | **$175** | **63 / 120′** |

## 🗂️ CCAR-P 七大考域（官方考綱 v1.0, 2026-07）
1. Solution Design & Architecture — 17%
2. Claude Models, Prompting & Context Engineering — 13%
3. **Integration（RAG / MCP / authz / observability）— 19%（最重）**
4. Evaluation, Testing & Optimization — 16%
5. **Governance, Safety & Risk（GDPR/HIPAA/FedRAMP / HITL）— 14%**
6. Stakeholder Communication & Lifecycle — 14%
7. Developer Productivity & Operational Enablement — 7%

## 📌 備考策略
7 域裡 6 域屬「盤點已知」，主攻 3 塊：
- **Domain 5 合規**（GDPR/HIPAA/FedRAMP）← 唯一需從頭補的
- Domain 4 正式 eval（dataset / A/B / hallucination 歸因）
- Domain 3 authz 最小權限 + 大規模 observability 設計題

## ⚠️ 資料與免責
- CCAR-P 的 63 題/720 分/七域配分皆以 **官方考綱 PDF** 為準。
- CCAR-F 逐域配分為第三方整理，報名前以 **Anthropic Partner Academy** 內考綱為準。
- 自我測驗中「自製」題為依考綱推導，**非官方題**，僅供熟悉題型；「官方」題為考綱附的 sample。
- 本 repo 為個人備考整理，非 Anthropic 官方教材。

## 🔗 官方入口
- 報名/排期：[Pearson VUE — Claude Certification Program](https://www.pearsonvue.com/us/en/anthropic.html)
- 備考課程：Anthropic Partner Academy（免費，需 Claude Partner Network）
