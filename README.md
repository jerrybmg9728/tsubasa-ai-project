# Tsubasa AI Project

## 1. プロジェクト目的
- 社内AI基盤の構築
- 業務効率化
- ナレッジ蓄積
- 経営判断支援

## 2. ビジョン
Tsubasa AI Project は、株式会社エコツバサ貿易の業務・知識・判断を支える社内AI基盤を構築するプロジェクトです。  
まずは「社内AI相談室」として現場で使える形から立ち上げ、段階的に社内知識の統合、業務支援、自動化へ拡張していきます。

## 3. 想定機能
- 社内チャットAI
- 会議議事録の自動整理・要約
- 社内ドキュメント検索
- タイヤ事業データ管理
- 営業支援
- 経営判断に必要な情報の可視化・整理

## 4. リポジトリ構成
```text
/docs
/src
/meeting-notes
```

### ディレクトリの役割
- `/docs` : 企画書、設計書、運用方針、要件定義
- `/src` : 実装コード
- `/meeting-notes` : 会議メモ、議事録、決定事項ログ

## 5. 開発体制

### 役割分担
- **Jerry**: オーナー / 意思決定者
- **Nova (OpenClaw)**: Jerryの個人秘書AI / 企画整理 / 要件整理 / Markdown管理 / 進行管理
- **ChatGPT**: 発想支援 / 文章化 / 調査補助
- **Claude Code**: 実装 / リファクタ / 重い開発作業
- **Codex**: 実装補助 / 技術検討 / コード生成

### 開発フロー
```mermaid
flowchart TD
    A[Jerry<br/>オーナー / 意思決定者] --> B[Nova (OpenClaw)<br/>個人秘書AI / PM補助]
    B --> C[docs/01-ideas.md<br/>アイデア・課題・要望を蓄積]
    C --> D[整理・構造化<br/>Nova / ChatGPT]
    D --> E[docs/02-priorities.md<br/>優先順位を整理]
    E --> F[docs/03-mvp-plan.md<br/>最初に作る範囲を定義]
    F --> G[Claude Code / Codex<br/>実装・開発・技術検討]
    G --> H[テスト・改善・ナレッジ蓄積]
```

## 6. 今日までの決定事項
- GitHubリポジトリを作成して管理する
- private運用を前提とする
- 段階導入で進める
  - Phase 1: 社内AI相談室
  - Phase 2: 社内知識検索
  - Phase 3: 一部業務自動化
- AIチーム分業で開発を進める

## 7. 次アクション
- `docs/01-ideas.md` を作成し、アイデアを書き溜める
- `docs/02-priorities.md` を作成し、優先順位を整理する
- `docs/03-mvp-plan.md` を作成し、MVP範囲を定義する
- 優先ユースケースを確定する
- 使用技術・構成案を整理する
