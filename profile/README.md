# 🏛️ Standard Architecture Blueprint (SAB) Project
> **"Building robust systems through logical rigor and AP Syllabus standards."**

本プロジェクトは、応用情報技術者試験（AP）のシラバスに基づき、エンタープライズITにおけるデファクトスタンダードなアーキテクチャを実証・習得するための「開発帝国」である。

---

## 🎯 1. Strategic Objective

本帝国の目的は、単なるコードの実装ではなく、高度IT人材として必要な「設計の正当性」を論理的に証明することにある。

### 🎓 AP試験範囲との対応
| 領域 | 対応項目 | 実装への反映 |
| :--- | :--- | :--- |
| **ストラテジ** | EA（エンタープライズアーキテクチャ） | Unit 00 による全体最適化とガバナンス |
| **マネジメント** | 開発プロセス・品質管理 | Template による標準化と命令網羅(C0)の追求 |
| **テクノロジ** | セキュリティ、ネットワーク、DB | platform-auth による認証認可の一元管理 |

---

## 🏗️ 2. Structural Definition (3 Units / 4 Layers)

### 🛡️ Unit 00: Foundation & Governance
**「共通フレーム」と「基盤」の定義。全ての行動の根拠。**
- `standards`: アーキテクチャ憲法、ADR、命名規約、APシラバス準拠の設計指針。
- `infra-platform`: コンテナ仮想化（Docker）による共通実行環境のIaC。
- `common-library`: 再利用性を高める共通コンポーネント（Java / TS / Py）。
- `.github`: 組織全体のポータルと管理。

### 🛠️ Unit 01: Factory (Templates)
**「生産性」と「標準化」の追求。開発速度を戦術的優位性に変える。**
- `template-java-spring`: SoR開発用金型（Java 17 / Spring Boot 3.x）。
- `template-angular-spa`: SoE開発用金型（Angular / TypeScript）。
- `template-python-ml` SoI開発用金型（Python / Analysis）。

### 🚀 Unit 02: Strategic Applications
**「ドメイン」と「価値」の実装。実戦配備される軍事資産。**
- 🟦 **Platform**: `platform-auth`（認証認可の外部化）
- 🟥 **SoR**: `sor-accounting`, `sor-inventory`, `sor-hr-payroll`（データ整合性重視）
- 🟧 **SoE**: `soe-portal`, `soe-workflow`（UX・スピード重視）
- 🟩 **SoI**: `soi-analytics`（意思決定支援・BI）

---

## ⚔️ 3. Implementation Disciplines (Military Logic)

1. **Model Driven**: 実装前に必ずクラス図、シーケンス図、ER図を Mermaid で記述し、設計の「静的・動的構造」を確定させる。
2. **De-facto Standard**: 独自実装（オレオレ実装）を排除。Spring Ecosystem や Angular の流儀に従い、保守性を最大化する。
3. **Traceability**: 技術選定の理由は、AP試験の用語を用いてドキュメント化し、「なぜその技術か」を論理的に説明可能にする。
4. **Security by Design**: `platform-auth` を中心とした OAuth2.0/OIDC に準拠し、各サービスは無状態（Stateless）を維持する。

---

## 📅 Roadmap
- **Phase 1**: Unit 00 基盤整備 & `common-library` 実装 👈 **NOW**
- **Phase 2**: `platform-auth` 稼働 & 各 Template 構築
- **Phase 3**: SoR / SoE アプリケーションの順次展開

---
© 2026 Standard Architecture Blueprint. Managed by **System Architect**.
