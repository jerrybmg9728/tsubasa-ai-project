# Tsubasa AI Project - System Overview

## 1. Project Positioning

Tsubasa AI Project is not just a chatbot project.
It is a foundation project to connect internal knowledge, daily operations, and management decisions through AI conversation.

If developed well, it can become a kind of internal operating system for the company.

---

## 2. Structural View

This project is easiest to understand in three layers.

### Layer 1: Information Organization Layer
Purpose: make company knowledge searchable and maintainable.

Main tasks:
- Collect documents and business data
- Classify information by type and purpose
- Standardize naming rules
- Create update and maintenance rules
- Define access control boundaries

This layer is the foundation. If this is weak, AI quality will be unstable.

### Layer 2: AI Conversation Layer
Purpose: allow employees to access information naturally through chat.

Main functions:
- Employees ask questions in natural language
- AI retrieves related information
- AI answers with sources
- Chat UI optimized for simple internal use

Example questions:
- What is the price for 385/65R22.5?
- Can you find the past quotation for company X?
- Do we have customs documents from 2023?
- What are the specs for this model?

### Layer 3: Management Improvement Layer
Purpose: use interaction data to improve the company itself.

Main functions:
- Analyze employee question logs
- Detect repeated business bottlenecks
- Identify education gaps
- Discover inefficient tasks
- Find automation opportunities

This is the long-term value layer, but it should come after the first two layers are stable.

---

## 3. Strategic Evaluation from Three Perspectives

### A. AI Assistant Perspective
Strengths:
- Practical and easy to imagine in real use
- Strong natural-language interaction concept
- Business data is concrete, not abstract
- Knowledge accumulation and process improvement are linked

Risks:
- Scope is too broad if everything is included at once
- AI quality depends more on information structure than on model power
- Naming, document hygiene, update rules, and source clarity are critical

Key insight:
> The real challenge is not building a smart AI. It is building an answerable information structure.

### B. Management Perspective
Business value:
- Reduces time spent searching for information
- Reduces dependence on specific individuals
- Improves training and standardization
- Creates visibility into business problems through question logs

Management success factors:
- Employees actually use it
- Answers are trusted
- Information stays updated
- Access rights are properly controlled
- Ongoing maintenance is clearly owned

Key insight:
> This is not only an AI development project. It is an internal information flow reform project.

### C. Programming Perspective
Technically sound direction:
- Frontend: Chat UI
- Backend: workflow / auth / retrieval
- Database: PostgreSQL + pgvector
- Prompts: controlled AI behavior
- Docs: architecture, meeting notes, operational rules

Technical risks:
- PDF / OCR quality issues
- Old versions of files being retrieved
- Weak source attribution
- Access control complexity
- Hallucination risk from incomplete internal data

Key insight:
> The first technical decision should be what to search first, not what to automate first.

---

## 4. Recommended Rollout

### MVP Focus
The best first cut is narrow and practical:

- Tire price search
- Product document search
- Model/spec lookup
- Basic chat UI

MVP goal:
> Employees get used to asking AI for practical answers.

### After MVP
Second wave:
- Past quotations
- Customs documents
- OCR support

Third wave:
- Financial data
- Department-based access control
- More structured internal knowledge

Long-term expansion:
- Log analysis
- Training improvement
- Workflow automation
- AI agent functions

---

## 5. Strengths of the Project

- Directly tied to real business operations
- Clear and valuable use cases
- Natural conversation interface lowers training cost
- User logs become business intelligence assets
- Can expand step by step without redesigning the whole concept

---

## 6. Risks and Watchouts

- Scope expansion too early
- Poor document governance reducing answer quality
- Unclear ownership for maintenance
- Sensitive data needs clear permission design
- Character/mascot concept must not weaken business trust

Important balance:
> Friendly is good, but reliable is essential.

---

## 7. Core Conclusion

Tsubasa AI Project is structurally strong.
It has real business grounding, which makes it far more viable than a generic AI idea.

Its success will not depend mainly on model intelligence.
Its success will depend on:
- narrowing the first use case,
- organizing source data well,
- keeping answers traceable,
- and building trust through stable operation.

The most important principle is:
> Start narrow, prove value, then expand.
