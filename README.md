# Tsubasa AI Project

社内AIナレッジアシスタントプロジェクト

---

## プロジェクト概要

Tsubasa AI Project は、社内業務効率化を目的とした AI ナレッジアシスタント構築プロジェクトです。

社員が自然言語でAIと会話しながら、社内資料・業務データ・価格情報・通関資料・財務情報などに素早くアクセスできる環境を作ります。

最終的には、単なる検索ツールではなく、

> 「社員一人ひとりを支援する AI パートナー」

として、会社全体の生産性向上を目指します。

---

## プロジェクトビジョン

### 1. 社内ナレッジの統合

散在している資料を一元化し、社員が必要な情報を即座に取得できる状態を作る。

対象データ：

- タイヤ価格表
- 商品資料
- タイヤ型番・スペック
- 顧客向け資料
- 通関書類
- 過去見積
- 財務資料
- SOP / 社内ルール

---

### 2. AI社員アシスタント化

社員は AI とチャット形式で会話する。

例：

「385/65R22.5 の価格を教えて」

「○○社の過去の見積を探して」

「2023年の通関資料ある？」

「この商品のスペックは？」

AIは出典付きで回答。

---

### 3. 経営改善

社員の質問ログを分析し、

- 業務上の課題
- 教育不足領域
- 非効率業務
- 自動化可能領域

を発見する。

最終的に：

> AI を活用した継続的な業務改善

を実現する。

---

## システム構想

### Frontend

- Web Application
- PC / iPad / Smartphone 対応
- Chat UI
- 吉祥物ベースの会話体験

候補：

- Next.js
- React

---

### Backend

- Dify
- Agent Workflow
- RAG System

---

### AI Models

Primary:
- OpenAI (GPT)

Secondary:
- Claude

将来的には：
- OSS model
- local LLM

も検討。

---

### Database

- PostgreSQL
- pgvector

---

### Hardware

- Mac Studio
- NAS
- Local storage

---

## 開発ロードマップ

### Phase 1 (MVP)

最小構成：

- タイヤ価格検索
- 商品資料検索
- チャットUI

目的：

> 社員が AI に慣れる

---

### Phase 2

追加：

- 通関資料
- 過去見積
- OCR

目的：

> 検索効率化

---

### Phase 3

追加：

- 財務データ
- 部門別権限

目的：

> 経営支援

---

### Phase 4

追加：

- 社員課題分析
- AI Agent
- 自動化

目的：

> AI Driven Company

---

## 吉祥物構想

社内AIアシスタントを「吉祥物キャラクター」として表現。

仮称：

翼ちゃん（Tsubasa AI）

社員が自然に話しかけられる存在を目指す。

---

## Repository Structure

```text
/docs
/docs/meeting-notes
/docs/architecture
/frontend
/backend
/infra
/prompts
/assets
```

---

## Current Status

Planning Phase (v0.1)

- [x] Vision Defined
- [x] Architecture Discussion
- [x] GitHub Repository Created
- [ ] MVP Development
- [ ] Dify Integration
- [ ] Employee Testing

---

## Long-Term Goal

Build an internal AI ecosystem that continuously improves business operations, employee productivity, and management efficiency.
