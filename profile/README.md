# Standard Architecture Blueprint (SAB) Project

## 1. Strategic Objective
本プロジェクトは、**応用情報技術者試験（AP）**のシラバスに基づき、エンタープライズITにおける**デファクトスタンダード**なアーキテクチャを実証・習得するための「開発帝国」である。

### 🎓 AP試験範囲との対応
* **ストラテジ領域**: EA（エンタープライズアーキテクチャ）、業務プロセスのモデリング（BPMN）。
* **アーキテクチャ領域**: SoR/SoEの分離、マイクロサービス、疎結合設計、デザインパターン。
* **技術要素**: セキュリティ（OAuth2.0/OIDC）、データベース（ACID特性/正規化）、ネットワーク。

---

## 2. Structural Definition (3 Units / 4 Layers)

### 🛡️ Unit 00: Foundation & Governance
> **「共通フレーム」と「基盤」の定義。**
* **`standards`**: アーキテクチャ憲法、ADR、命名規約、APシラバス準拠の設計指針。
* **`infra-platform`**: コンテナ仮想化（Docker）による共通実行環境。
* **`common-library`**: 再利用性を高める共通コンポーネント。
* **`.github`**: 組織全体のポータルと管理。

### 🛠️ Unit 01: Factory (Templates)
> **「生産性」と「標準化」の追求。**
* **`template-java-spring`**: SoR開発用金型（Java 17 / Spring Boot 3.x）。
* **`template-angular-spa`**: SoE開発用金型（Angular / TypeScript）。
* **`template-python-ml`**: SoI開発用金型（Python / Analysis）。

### 🚀 Unit 02: Strategic Applications
> **「ドメイン」と「価値」の実装。**
* **🟦 Platform**: `platform-auth`（認証認可の外部化）
* **🟥 SoR**: `sor-accounting`, `sor-inventory`, `sor-hr-payroll`（データ整合性重視）
* **🟧 SoE**: `soe-portal`, `soe-workflow`（UX・スピード重視）
* **🟩 SoI**: `soi-analytics`（意思決定支援・BI）

---

## 3. Implementation Disciplines (Military Logic)
1. **Model Driven**: 実装前に必ずクラス図、シーケンス図、ER図をMermaidで記述する。
2. **De-facto Standard**: 独自実装を避け、広く普及しているライブラリとパターンを採用する。
3. **Traceability**: 技術選定の理由は、AP試験の用語を用いてドキュメント化する。

---
© 2026 Standard Architecture Blueprint. Building robust systems through logical rigor.
