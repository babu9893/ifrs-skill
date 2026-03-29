---
name: ifrs
description: Use when answering questions about IFRS standards, financial reporting, revenue recognition, lease accounting, impairment, disclosure requirements, IFRS compliance checks, audit support, or transitioning from local GAAP to IFRS.
---

# IFRS Skill

## Decision Flow

### 1. Detect Task Type

Classify the request before responding:

- **guidance** — how a standard works or how to apply it
- **compliance-audit** — reviewing transactions or disclosures against IFRS requirements
- **transition** — moving from local GAAP (e.g., US GAAP, UK GAAP) to IFRS
- **general-learning** — foundational questions, exam prep, plain-language explanations
- **mixed** — multiple types; address each in sequence

### 2. Detect Audience

- **Professional (default)** — assume the user is an accountant, auditor, financial analyst, or preparer; use precise IFRS terminology
- **Learner mode** — if the user signals they are studying, new to IFRS, or wants plain-language explanations, simplify terminology and add examples

### 3. Select Output Format

| Task Type | Format |
|---|---|
| compliance-audit | Structured checklist or table; cite paragraph references |
| guidance / technical | Cited narrative; include standard number and paragraph |
| transition | Step-by-step with before/after comparison |
| general-learning | Conversational; analogies welcome; cite standards lightly |

### 4. Verify Currency

Before citing effective dates, amendment status, or jurisdiction timelines, use web search to confirm currency. IFRS standards are updated regularly by the IASB; do not rely on training data for effective dates or transitional provisions.

---

## Supporting Files

| File | Purpose |
|---|---|
| `standards-reference.md` | Standard-by-standard details (IFRS 9, 15, 16, IAS 36, etc.) |
| `workflows.md` | Multi-step procedures (e.g., ECL calculation, lease amortisation) |
| `compliance-templates.md` | Structured output templates for disclosure checklists and audit support |
| `transition-guide.md` | GAAP-to-IFRS transition planning and exemptions |
