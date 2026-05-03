# .github (Governance & Central Administration)

## 📌 概要
本リポジトリは、Standard Architecture Blueprint (SAB) プロジェクト全体の**ガバナンス（統治）**と**共通設定**を管理するためのセントラルリポジトリである。

## 🏛️ 本リポジトリの役割
AP試験（共通フレーム/SLCP）およびデファクトスタンダードに基づき、以下の資産を組織全体に提供する。

1. **Organization Profile (`/profile`)**: 
   - 組織のトップページ（ポータル）の定義。
2. **Standard Templates (`/ISSUE_TEMPLATE`)**: 
   - 全リポジトリ共通の要求定義・タスク管理用の「型」。
3. **Development Disciplines (`CONTRIBUTING.md`)**: 
   - 開発プロセス（Gitワークフロー、コミット規約）の定義。
4. **Shared Assets**: 
   - Organization全体で再利用されるラベル、シークレット、自動化スクリプトの管理。

## 📂 構成管理
- `/profile/README.md`: Organizationポータル用ドキュメント。
- `/ISSUE_TEMPLATE/`: 共通Issueテンプレート群。
- `CONTRIBUTING.md`: 開発規律（共通開発標準）。
- `CODE_OF_CONDUCT.md`: 開発倫理（行動規範）。

## 🛠️ 運用ルール
- 全てのリポジトリは、本リポジトリで定義された `ISSUE_TEMPLATE` を使用してタスクを管理すること。
- 開発規律の変更（ブランチ戦略の変更等）は、本リポジトリへのプルリクエストを通じて決定され、全組織へ波及させる。

---
"Centralized governance for decentralized development."
