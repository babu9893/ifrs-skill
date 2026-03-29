# GAAP-to-IFRS Transition Guide

This guide provides framework-agnostic guidance for entities transitioning from local GAAP to IFRS. It focuses on IFRS requirements and flags common difference areas rather than mapping from any specific national framework. For detailed IFRS 1 first-time adoption steps, see the IFRS 1 workflow in `workflows.md`. For the gap analysis template, see `compliance-templates.md`.

---

## 1. Overview

### What Is an IFRS Transition?

An IFRS transition is the process of converting an entity's financial reporting from a local (national) GAAP to International Financial Reporting Standards. The governing standard is **IFRS 1 — First-time Adoption of International Financial Reporting Standards**, which:

- Requires full retrospective application of all IFRS standards effective at the first IFRS reporting date, subject to specific mandatory exceptions and optional exemptions.
- Mandates an opening IFRS balance sheet at the **date of transition** (the beginning of the earliest comparative period).
- Requires at least one year of comparative information prepared under IFRS.
- Provides a structured set of exemptions to reduce the cost of transition where full retrospective application would be impracticable or excessively burdensome.

> **Cross-reference:** For the complete step-by-step IFRS 1 adoption procedure, see the IFRS 1 First-Time Adoption workflow in `workflows.md`.

### Governing Principles

1. **Retrospective application** — Apply each IFRS standard as if it had always been applied, unless an exemption is elected.
2. **Consistency** — Use the same accounting policies throughout all periods presented in the first IFRS financial statements.
3. **Transparency** — Provide reconciliations from previous GAAP to IFRS so users can understand the impact of the transition.

---

## 2. Key Dates

### Date Framework

| Date | Definition | Example (FY2026 Adoption, 1-Year Comparatives) |
|---|---|---|
| **Date of transition** | Beginning of the earliest comparative period presented under IFRS | 1 January 2025 |
| **Comparative period end** | End of the comparative period | 31 December 2025 |
| **First IFRS reporting date** | End of the first annual reporting period under IFRS | 31 December 2026 |

### Timeline Illustration (FY2026 Adoption)

```
1 Jan 2025              31 Dec 2025             31 Dec 2026
    |                       |                       |
    |--- Comparative -------|--- First IFRS Year ---|
    |                       |                       |
 Opening IFRS          Comparative             First IFRS
 balance sheet         financial              financial
 (date of             statements              statements
  transition)          (restated)             (published)
```

### What Happens at Each Date

- **1 January 2025 (date of transition):** Prepare an opening IFRS balance sheet. Recognise all assets and liabilities required by IFRS, derecognise items not permitted, reclassify as needed, and measure everything under IFRS. Adjustments go to retained earnings (or another equity category if appropriate).
- **31 December 2025 (comparative period end):** Present a full set of IFRS-compliant comparative financial statements for this period.
- **31 December 2026 (first IFRS reporting date):** Publish the first complete set of IFRS financial statements, including the IFRS 1 reconciliations and disclosures.

---

## 3. Common Difference Areas

The following ten areas represent the most frequent sources of adjustment when transitioning from local GAAP to IFRS. Each entry describes the IFRS requirement and flags typical differences found under common national frameworks.

### 3.1 Revenue Recognition — IFRS 15

| Aspect | IFRS Requirement | Common Local GAAP Difference |
|---|---|---|
| **Model** | Five-step model based on transfer of control | Risks-and-rewards model; revenue recognised at a single point (e.g., delivery) |
| **Multiple performance obligations** | Allocate transaction price to each distinct performance obligation using standalone selling prices | Bundled arrangements often recognised as a single unit |
| **Variable consideration** | Estimate and constrain variable consideration at contract inception | Variable amounts recognised only when finalised or when uncertainty resolved |
| **Contract costs** | Capitalise incremental costs of obtaining a contract (IFRS 15.91-94) | Sales commissions and bid costs typically expensed as incurred |
| **Timing** | Recognise over time if criteria in IFRS 15.35 are met; otherwise at a point in time | Percentage-of-completion may apply under different criteria or not at all |

**Transition action:** Restate open contracts at the date of transition. Consider the IFRS 1 optional exemption for completed contracts.

### 3.2 Leases — IFRS 16

| Aspect | IFRS Requirement | Common Local GAAP Difference |
|---|---|---|
| **Lessee model** | Single on-balance-sheet model: recognise right-of-use asset and lease liability for virtually all leases | Operating leases kept off balance sheet; only finance/capital leases on balance sheet |
| **Measurement** | Initial measurement at present value of lease payments; subsequent depreciation of ROU asset and interest on liability | Operating lease expense recognised on straight-line basis with no balance sheet impact |
| **Short-term / low-value** | Optional exemptions for leases under 12 months or of low-value underlying assets | No equivalent distinction needed when operating leases are off balance sheet |
| **Sale and leaseback** | Apply IFRS 15 to determine whether transfer is a sale; if so, measure ROU asset proportionally | May recognise full gain on sale; leaseback treated as new operating lease |

**Transition action:** Inventory all lease contracts. Quantify the balance sheet gross-up. IFRS 1 permits measuring the lease liability at transition date (rather than at lease inception) as a practical expedient.

### 3.3 Financial Instruments — IFRS 9

| Aspect | IFRS Requirement | Common Local GAAP Difference |
|---|---|---|
| **Classification** | Three categories based on business model and contractual cash flow characteristics: amortised cost, FVOCI, FVTPL | Four or more categories (held-to-maturity, available-for-sale, loans and receivables, FVTPL) |
| **Impairment** | Expected credit loss (ECL) model — forward-looking, three-stage approach | Incurred loss model — impairment recognised only after a loss event occurs |
| **Hedge accounting** | Simplified qualifying criteria; more hedging strategies eligible; risk components of non-financial items hedgeable | More restrictive bright-line effectiveness tests (e.g., 80-125% corridor) |
| **Equity investments** | Irrevocable FVOCI election (no recycling to P&L); otherwise FVTPL | May permit cost method for unquoted equities or recycling of AFS gains |

**Transition action:** Reclassify financial assets based on IFRS 9 criteria. Calculate ECL allowances at the date of transition. Review hedge documentation for IFRS 9 compliance.

### 3.4 Employee Benefits — IAS 19

| Aspect | IFRS Requirement | Common Local GAAP Difference |
|---|---|---|
| **Defined benefit measurement** | Project unit credit method; remeasurements (actuarial gains/losses) in OCI with no recycling | Corridor approach permitted (defer and amortise actuarial gains/losses); or immediate P&L recognition |
| **Discount rate** | High-quality corporate bonds (or government bonds where no deep market exists) | May use different benchmark rates |
| **Past service cost** | Recognise immediately in P&L when plan amendment occurs | Amortise over remaining service period |
| **Multi-employer plans** | Account as defined contribution unless sufficient information for defined benefit accounting | Treatment varies; some frameworks allow defined contribution accounting in all cases |

**Transition action:** Obtain actuarial valuations at the date of transition. Recognise the full net defined benefit liability/asset. IFRS 1 permits cumulative actuarial gains and losses to be reset to zero at the date of transition.

### 3.5 Impairment of Non-Financial Assets — IAS 36

| Aspect | IFRS Requirement | Common Local GAAP Difference |
|---|---|---|
| **Trigger** | Impairment test when indicators exist; annual for goodwill and indefinite-life intangibles | Some frameworks require annual testing for all long-lived assets or have different trigger indicators |
| **Recoverable amount** | Higher of fair value less costs of disposal and value in use (discounted cash flows) | Undiscounted cash flow test as a first screen; impairment measured differently |
| **Cash-generating units** | Test at CGU level (smallest group generating independent cash inflows) | May test at a different level of aggregation (e.g., reporting unit, asset group) |
| **Reversal** | Reversal required when conditions change (except for goodwill impairment — never reversed) | Some frameworks prohibit reversal of any impairment |

**Transition action:** Identify CGUs. Test goodwill and indefinite-life intangibles at the date of transition. Consider the IFRS 1 deemed cost exemption for assets where historical IFRS cost would be difficult to reconstruct.

### 3.6 Property, Plant and Equipment — IAS 16

| Aspect | IFRS Requirement | Common Local GAAP Difference |
|---|---|---|
| **Component depreciation** | Each significant component of an asset depreciated separately | Single useful life for the whole asset; no component accounting |
| **Revaluation model** | Permitted as an accounting policy (class-by-class election) | Revaluation prohibited in some frameworks; or permitted but with different mechanics |
| **Residual value** | Review at least annually; based on current prices | Set at acquisition and rarely updated |
| **Borrowing costs** | IAS 23 requires capitalisation for qualifying assets | May be expensed or capitalised at entity's option |
| **Decommissioning** | Include in cost with corresponding provision (IAS 37 / IFRIC 1) | Often not recognised until expenditure incurred |

**Transition action:** Componentise major assets. Reassess useful lives and residual values. Elect fair value or previous-GAAP revaluation as deemed cost under IFRS 1 if full retrospective cost data is unavailable.

### 3.7 Intangible Assets — IAS 38

| Aspect | IFRS Requirement | Common Local GAAP Difference |
|---|---|---|
| **Development costs** | Capitalise when all six IAS 38.57 criteria are met | Expense all R&D as incurred; or capitalise under different criteria |
| **Useful life** | Indefinite life permitted (no amortisation; annual impairment test instead) | All intangibles amortised over a maximum period (e.g., 10 or 20 years) |
| **Internally generated** | Internally generated brands, mastheads, customer lists — not recognised | Some frameworks permit recognition of certain internally generated intangibles |
| **Revaluation** | Permitted only if active market exists (rare in practice) | Revaluation typically prohibited |

**Transition action:** Review capitalised development costs against IAS 38.57 criteria. Derecognise any internally generated intangibles not meeting IFRS recognition criteria. Assess useful lives (finite vs indefinite).

### 3.8 Provisions and Contingencies — IAS 37

| Aspect | IFRS Requirement | Common Local GAAP Difference |
|---|---|---|
| **Recognition threshold** | "Probable" means more likely than not (>50%) | "Probable" may mean a higher threshold (e.g., ~75% in some frameworks) |
| **Measurement** | Best estimate; discount to present value if time value of money is material | Undiscounted amounts; or range-based measurement (e.g., low end of range) |
| **Restructuring** | Recognise only when detailed formal plan exists and valid expectation raised | Earlier recognition permitted based on board approval alone |
| **Contingent liabilities** | Disclose but do not recognise (unless acquired in a business combination) | Treatment varies; some frameworks require accrual at lower probability thresholds |

**Transition action:** Reassess all existing provisions against IAS 37 criteria. Discount long-term provisions. Review contingent liabilities for disclosure adequacy.

### 3.9 Consolidation and Group Accounting — IFRS 10

| Aspect | IFRS Requirement | Common Local GAAP Difference |
|---|---|---|
| **Control model** | Consolidate when investor has power, exposure to variable returns, and ability to use power to affect returns | Voting-interest model (majority of voting rights triggers consolidation); or risks-and-rewards model |
| **Structured entities** | Assessed under same control model; consolidate if controlled | Separate evaluation framework (e.g., variable interest entity model) with different criteria |
| **Investment entities** | Exception from consolidation; measure subsidiaries at FVTPL (IFRS 10.31-33) | No equivalent exception; all subsidiaries consolidated |
| **Non-controlling interests** | Measured at fair value or proportionate share of net assets (election per combination) | Typically measured at book value of proportionate net assets |

**Transition action:** Reassess control conclusions for all investees. Identify structured entities. Consider the IFRS 1 exemption for business combinations that occurred before the date of transition.

### 3.10 Presentation and Disclosure — IAS 1

| Aspect | IFRS Requirement | Common Local GAAP Difference |
|---|---|---|
| **Complete set of statements** | Statement of financial position, profit or loss and OCI, changes in equity, cash flows, and notes | Some frameworks do not require a statement of changes in equity or OCI as a separate statement |
| **OCI classification** | Items that will and will not be reclassified to P&L must be presented separately | OCI may not be required or may have different classification rules |
| **Current/non-current distinction** | Required unless a liquidity-based presentation is more relevant | Some frameworks mandate a different ordering or do not require the distinction |
| **Significant judgements and estimates** | Disclose key sources of estimation uncertainty and critical judgements (IAS 1.122-133) | Disclosure requirements may be less specific |
| **Comparative information** | Minimum one year of comparative information; three balance sheets if retrospective restatement | One year typical but specific requirements vary |

**Transition action:** Redesign the chart of accounts and financial statement templates. Map local GAAP line items to IAS 1 presentation requirements. Prepare IFRS-compliant note disclosures.

---

## 4. Transition Project Planning

### Phase 1: Assessment (3-6 Months Before Date of Transition)

**Objective:** Understand the scope of change and build the business case.

1. **Perform a diagnostic gap analysis** — Compare current accounting policies with IFRS requirements across all material areas. Use the gap analysis template in `compliance-templates.md`.
2. **Quantify the expected impact** — Estimate the effect on key financial metrics (equity, net income, leverage ratios, debt covenants).
3. **Identify data and system requirements** — Determine what additional data capture, system modifications, or new subledgers are needed (e.g., lease system for IFRS 16, ECL model for IFRS 9).
4. **Assess IFRS 1 exemption elections** — Perform a preliminary assessment of which optional exemptions to elect (see Section 5 below).
5. **Establish governance** — Appoint a transition project team, define roles (finance, IT, external advisors, auditors), and set up a steering committee.
6. **Develop project timeline and budget** — Map all workstreams, milestones, and resource requirements against the key dates in Section 2.

### Phase 2: Preparation (Date of Transition to End of Comparative Period)

**Objective:** Build IFRS-ready processes and prepare the opening balance sheet.

1. **Draft IFRS accounting policy manual** — Document the entity's IFRS accounting policies, including elections and exemptions.
2. **Prepare the opening IFRS balance sheet** — Recognise, derecognise, reclassify, and remeasure all items as required by IFRS. Record adjustments to retained earnings (or other equity).
3. **Implement dual reporting** — Run parallel local GAAP and IFRS reporting during the comparative period to build confidence and test processes.
4. **Configure systems and controls** — Implement system changes, new chart of accounts, IFRS-compliant subledgers, and internal controls over IFRS reporting.
5. **Train finance staff** — Conduct IFRS technical training tailored to the entity's specific difference areas and new processes.
6. **Engage auditors early** — Discuss the opening balance sheet, policy elections, and transition adjustments with external auditors to avoid surprises.

### Phase 3: Execution (Comparative Period to First IFRS Reporting Date)

**Objective:** Produce the first complete set of IFRS financial statements.

1. **Prepare comparative IFRS financial statements** — Compile the full-year comparative period financial statements under IFRS.
2. **Prepare IFRS 1 reconciliations** — Build the required reconciliations (see Section 6 below) from previous GAAP equity and profit or loss to IFRS.
3. **Draft first IFRS financial statements** — Prepare the complete financial statements for the first IFRS reporting period, including all required notes and IFRS 1 disclosures.
4. **Obtain audit sign-off** — Work with external auditors to complete the audit of the first IFRS financial statements, including the opening balance sheet and comparative period.
5. **Communicate to stakeholders** — Brief investors, analysts, lenders, regulators, and board members on the impact of the transition and key changes from prior reporting.

---

## 5. IFRS 1 Exemption Decision Framework

IFRS 1 provides optional exemptions from full retrospective application for specific areas. The decision to elect or not should be deliberate and documented.

### Decision Factors

| Factor | Elect Exemption | Do Not Elect Exemption |
|---|---|---|
| **Cost of retrospective application** | High — historical data is unavailable or would require excessive effort to reconstruct | Low — historical records are complete and accessible |
| **Data availability** | Source data for retrospective application does not exist or is unreliable | Reliable data exists for the entire retrospective period |
| **Comparability** | Exemption provides a reasonable starting point; limited impact on trend analysis | Full retrospective application provides more meaningful comparatives |
| **Subsequent measurement complexity** | Exemption simplifies ongoing measurement (e.g., deemed cost avoids tracking historical IFRS depreciation) | Full retrospective values align better with ongoing IFRS measurement |
| **Stakeholder expectations** | Users of financial statements accept the exemption approach | Investors or regulators prefer full retrospective figures |

### Key Optional Exemptions

| Exemption Area | What It Permits | When to Consider Electing |
|---|---|---|
| **Business combinations (IFRS 1.C1-C5)** | Do not restate business combinations before the date of transition | Acquisitions occurred many years ago; purchase price allocation data unavailable |
| **Deemed cost for PP&E/intangibles (IFRS 1.D5-D8)** | Use fair value or previous GAAP revaluation as deemed cost at the date of transition | Historical IFRS cost cannot be reliably determined; assets have been in use for many years |
| **Cumulative translation differences (IFRS 1.D12-D13)** | Reset cumulative translation differences to zero at the date of transition | Reconstructing historical translation adjustments is impracticable |
| **Employee benefits (IFRS 1.D10-D11)** | Reset cumulative actuarial gains and losses to zero at the date of transition | Actuarial records for prior periods are incomplete |
| **Leases (IFRS 1.D9B)** | Measure lease liability at the date of transition rather than at lease inception | Large volume of leases; inception-date data unavailable |
| **Share-based payment (IFRS 1.D2-D3)** | Do not apply IFRS 2 to awards vested before the date of transition | Share-based payment data for historical grants is incomplete |
| **Borrowing costs (IFRS 1.D23)** | Apply IAS 23 prospectively from the date of transition | Historical capitalisation records under IFRS criteria do not exist |

### Documentation Requirement

For every exemption elected or not elected, document:

- The exemption reference (IFRS 1 paragraph)
- The rationale for electing or not electing
- The quantitative impact (or the reason full quantification was impracticable)
- Approval by the transition steering committee

This documentation supports audit evidence and regulatory review.

---

## 6. Reconciliation Checklist

IFRS 1.24-28 requires specific reconciliations in the first IFRS financial statements. Use this checklist to ensure completeness.

### Required Reconciliations

- [ ] **Equity reconciliation at the date of transition** — Reconcile previous GAAP equity to IFRS equity at the opening balance sheet date (e.g., 1 January 2025)
- [ ] **Equity reconciliation at the end of the latest previous GAAP period** — Reconcile previous GAAP equity to IFRS equity at the comparative period end (e.g., 31 December 2025)
- [ ] **Profit or loss reconciliation for the latest previous GAAP period** — Reconcile previous GAAP profit or loss to IFRS for the comparative year (e.g., FY2025)
- [ ] **Total comprehensive income reconciliation** — If the entity presented a statement of comprehensive income under previous GAAP, reconcile total comprehensive income

### Reconciliation Content

For each reconciliation, ensure the following:

- [ ] **Starting balance clearly stated** — Previous GAAP amount with reference to the audited local GAAP financial statements
- [ ] **Individual adjustments separately identified** — Each IFRS adjustment shown as a separate line item with a description (e.g., "Capitalisation of operating leases under IFRS 16", "ECL adjustment under IFRS 9")
- [ ] **Tax effects of adjustments** — Deferred tax impact of each transition adjustment shown (IAS 12 applied to IFRS carrying amounts)
- [ ] **Non-controlling interest impact** — Adjustments allocated between owners of the parent and NCI where applicable
- [ ] **Narrative explanation of material adjustments** — Sufficient detail for users to understand the nature and drivers of each significant adjustment
- [ ] **Cross-reference to accounting policies** — Each adjustment linked to the relevant IFRS accounting policy in the notes
- [ ] **Impairment losses recognised or reversed** — Any impairment recognised (or previous impairment reversed) on transition separately disclosed (IFRS 1.24(c))
- [ ] **Fair value as deemed cost** — Where fair value or revaluation was used as deemed cost, disclose the aggregate amount and adjustments (IFRS 1.30)
- [ ] **Reclassification adjustments** — Items that changed classification without changing measurement (e.g., from one financial instrument category to another) separately identified
- [ ] **Consistency verified** — Reconciliations are internally consistent (opening equity + P&L adjustments + OCI adjustments = closing equity)

> **Cross-reference:** Use the IFRS 1 disclosure checklist in `compliance-templates.md` to ensure all first-time adoption disclosures are complete.

---

## Quick Reference: Related Skill Files

| File | Use For |
|---|---|
| `workflows.md` | IFRS 1 first-time adoption step-by-step workflow |
| `compliance-templates.md` | Gap analysis template, disclosure checklists |
| `standards-reference.md` | Detailed standard-by-standard guidance (IFRS 9, 15, 16, IAS 19, 36, 37, 38, etc.) |
