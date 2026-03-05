# ISO 17025 Skill — Examples (English)

Real prompt → response examples showing what this skill can do.

---

## 1. Audit Preparation — Process Requirements

**Prompt:**
```
/iso-17025 I have a PCA surveillance audit in 2 weeks.
Focus on clause 7 (process requirements). What should I prepare?
```

**Response:**

Here's your focused preparation checklist for **Clause 7 — Process Requirements**:

### 7.1 Review of Requests, Tenders and Contracts
**Have ready:**
- Recent contract/order review records (at least 10 from last 6 months)
- Evidence of communicating method changes to clients
- Records of any contract amendments and re-reviews

**Auditor will likely ask:** *"Show me how you reviewed this order. Did the client specify the method? How did you confirm you had the capability?"*

### 7.2 Selection, Verification and Validation of Methods
**Have ready:**
- Current method register/index
- Verification records for all standardized methods
- Validation reports for any non-standard or modified methods
- Evidence that personnel are using current method versions

**Auditor will likely ask:** *"When did you last verify this method? Show me the validation report for [method X]. What parameters did you validate?"*

**Common finding:** Outdated method versions still in use, or validation reports missing key parameters (LOD, LOQ, uncertainty).

### 7.5 Technical Records
**Have ready:**
- Sample of completed worksheets/records from recent tests
- Evidence that original data is preserved when corrections are made
- Demonstration that records allow reproduction of the activity

**Auditor will likely ask:** *"Show me the raw data for this report. Who made this correction and when? Can I trace this result back to the original measurement?"*

### 7.6 Measurement Uncertainty
**Have ready:**
- Uncertainty budgets for all methods in your scope
- Evidence of periodic review/update of uncertainty estimates
- Correct reporting format on certificates/reports

**Red flag:** If you added a new method since the last audit but haven't completed the uncertainty budget — do this NOW.

### 7.7 Ensuring Validity of Results
**Have ready:**
- QC charts (control charts) for routine methods
- PT/ILC participation records and analysis of results
- Actions taken for any out-of-control or unsatisfactory PT results
- Evidence of trend analysis

**Auditor will likely ask:** *"Show me your control charts for [method]. What was your last PT result? What action did you take for the z-score of 3.2?"*

### 7.8 Reporting
**Have ready:**
- Sample reports — verify ALL elements from 7.8.2.1 are present
- If you issue conformity statements — document your decision rules (7.8.6)
- Amended report examples (if any) — proper referencing to original

### Priority Actions (next 2 weeks):
1. **Verify all uncertainty budgets are current** — this is the #1 finding area
2. **Check PT results** — ensure all unsatisfactory results have documented corrective actions
3. **Review 5 recent reports** against 7.8.2.1 checklist — fix any template gaps
4. **Update control charts** — ensure they're current through today
5. **Check method register** — confirm all versions match what's actually in use

---

## 2. Gap Analysis — New Laboratory

**Prompt:**
```
/iso-17025 We're a small environmental water testing lab (5 people)
wanting to get ISO 17025 accreditation for the first time.
We test pH, conductivity, turbidity, and heavy metals (ICP-OES).
We have no formal QMS. Where do we start?
```

**Response:**

Here's a prioritized gap analysis and implementation roadmap for your water testing laboratory.

### Current Assessment: Starting from Zero QMS

#### Phase 1 — Foundation (Months 1-3) — HIGH PRIORITY

| Requirement | What You Need | Effort |
|-------------|--------------|--------|
| **5.3** Scope definition | Document exactly which tests, matrices, and ranges you'll seek accreditation for | 1 week |
| **5.5** Organizational structure | Org chart, job descriptions with responsibilities, reporting lines | 1 week |
| **8.2** Quality policy & manual | Quality policy statement + quality manual covering all clauses | 2-3 weeks |
| **6.2** Personnel competence | Competence criteria for each role, training records, authorization matrix | 2 weeks |
| **8.3-8.4** Document & record control | Document numbering system, approval workflow, record retention policy | 1 week |

#### Phase 2 — Technical Core (Months 3-6) — HIGH PRIORITY

| Requirement | What You Need | Effort |
|-------------|--------------|--------|
| **7.2** Method verification | Verify all 4 methods (pH, conductivity, turbidity, ICP-OES). Generate verification data | 4-6 weeks |
| **7.6** Measurement uncertainty | Uncertainty budgets for all parameters. ICP-OES will be most complex | 4-6 weeks |
| **6.4** Equipment management | Equipment list, calibration program, maintenance schedules, labels | 2 weeks |
| **6.5** Metrological traceability | Ensure all calibrations traceable to SI. CRMs from ISO 17034 producers | 1 week |
| **7.7** Quality assurance | QC program: control charts, blanks, duplicates, spikes. PT enrollment | 2 weeks |

#### Phase 3 — System Completion (Months 6-9)

| Requirement | What You Need |
|-------------|--------------|
| **4.1** Impartiality | Risk assessment, personnel declarations |
| **4.2** Confidentiality | NDAs, data handling procedure |
| **7.1** Contract review | Review procedure for incoming work |
| **7.4** Sample handling | Receipt, identification, storage, disposal procedures |
| **7.8** Reporting | Report templates meeting 7.8.2.1 requirements |
| **7.9-7.10** Complaints & nonconforming work | Documented procedures |
| **8.5** Risk & opportunities | Risk register |
| **8.7** Corrective actions | CA procedure with root cause analysis |

#### Phase 4 — Verification (Months 9-12)

| Activity | Purpose |
|----------|---------|
| **8.8** Internal audit | Full audit against all clauses — use an external auditor if needed |
| **8.9** Management review | First formal review with all required inputs (8.9.2 a-o) |
| Fix findings | Address all nonconformities from internal audit |
| Pre-assessment | Optional but recommended — PCA or consultant mock audit |
| **Apply to PCA** | Submit application with scope, methods, and supporting documentation |

### Budget Considerations for a 5-Person Lab
- **PT programs:** ~€2,000-4,000/year (enroll in at least 2 rounds for each parameter before applying)
- **CRMs:** ~€1,000-2,000/year for ICP-OES standards
- **Calibrations:** pH meters, conductivity meters, balances — ensure accredited calibration
- **PCA fees:** Application + assessment fees (check current PCA price list)
- **Consultant:** Consider 10-20 days of consultant support (~€5,000-15,000)

### Key Tip for Small Labs
With 5 people, keep your QMS lean. You don't need 200 pages of procedures. ISO 17025 says "documented to the extent necessary" (5.5c). Focus on what matters: competent people, validated methods, traceable measurements, and evidence that your results are reliable.

---

## 3. Method Validation Plan — Heavy Metals by ICP-MS

**Prompt:**
```
/iso-17025 I need to validate a method for determining Pb, Cd, As,
and Hg in drinking water by ICP-MS. We're extending our scope
from ICP-OES to ICP-MS for lower detection limits.
What validation plan should I follow?
```

**Response:**

### Validation Plan: Heavy Metals (Pb, Cd, As, Hg) in Drinking Water by ICP-MS

**Reference:** Clause 7.2.2 — This requires full validation because you're using a different technique (ICP-MS vs ICP-OES), even if based on a standard method.

#### 1. Scope
- **Analytes:** Pb, Cd, As, Hg
- **Matrix:** Drinking water (tap water, treated groundwater, treated surface water)
- **Expected range:** 0.05 – 50 µg/L (Pb, As), 0.01 – 10 µg/L (Cd), 0.02 – 5 µg/L (Hg)
- **Regulatory limits:** Pb 10 µg/L, Cd 5 µg/L, As 10 µg/L, Hg 1 µg/L (EU Directive 2020/2184)

#### 2. Validation Parameters

| Parameter | Design | Acceptance Criteria |
|-----------|--------|-------------------|
| **Selectivity** | Analyze 5 different blank waters, check for spectral interferences. Run interference check solution | No false positives >LOD; known interferences (ArCl on As-75) resolved by collision/reaction cell |
| **Linearity** | 6 calibration points + blank, 3 replicates each | R² > 0.999, residuals < ±10% |
| **Working range** | Defined by linearity study | LOQ to highest calibration point |
| **LOD** | 10 independent blank measurements × 3 days | LOD = 3 × SD(blanks). Must be < 1/10 regulatory limit |
| **LOQ** | 10 measurements at expected LOQ level | LOQ = 10 × SD(blanks). RSD < 10%. Must be < 1/3 regulatory limit |
| **Trueness (Recovery)** | Spike at 3 levels (LOQ, mid-range, high) in 3 different matrices, n=6 per level | Recovery 90-110% at mid/high, 80-120% at LOQ |
| **Repeatability** | 10 replicates at 3 concentration levels, same day | RSD < 5% (mid/high), < 10% (LOQ level) |
| **Intermediate precision** | 3 operators × 3 days × 3 replicates at 2 levels | RSD < 10% (mid), < 15% (LOQ level) |
| **Robustness** | Vary: acid concentration ±10%, rinse time ±20%, integration time ±20% | No significant change in results (t-test, p>0.05) |
| **Matrix effects** | Compare slopes of calibration in matrix vs pure standard | Matrix effect < ±15%, or use matrix-matched calibration / internal standards |
| **Measurement uncertainty** | Bottom-up budget based on validation data | U(expanded) < 30% at regulatory limit (k=2) |

#### 3. Special Considerations for Hg
- Hg requires special attention: memory effects, adsorption on glass
- Use gold (Au) as stabilizer in standards and samples
- Dedicated rinse protocol between samples
- Consider separate Hg determination if memory effects persist

#### 4. CRMs and QC Materials Required
- Certified multi-element CRM in water matrix (e.g., SPS-SW2, NIST 1640a)
- Single-element standards for Pb, Cd, As, Hg (traceable to SI)
- Internal standards: Rh, In, Bi (or as appropriate for your mass range)
- Blank water: ultra-pure water (18.2 MΩ·cm)

#### 5. Timeline
| Week | Activity |
|------|----------|
| 1 | Selectivity, linearity, working range |
| 2 | LOD, LOQ determination |
| 3-4 | Trueness (recovery) at 3 levels × 3 matrices |
| 4-5 | Repeatability and intermediate precision |
| 5 | Robustness testing |
| 6 | Data analysis, uncertainty calculation, report writing |

#### 6. Validation Report (per 7.2.2.4)
Must include fitness-for-purpose statement: *"The method is/is not fit for purpose for the determination of Pb, Cd, As, and Hg in drinking water at concentrations relevant to EU Directive 2020/2184 limits."*

---

## 4. Measurement Uncertainty — pH Measurement

**Prompt:**
```
/iso-17025 Help me create an uncertainty budget for pH measurement
in water samples. We use a Metrohm 913 pH meter calibrated with
buffer solutions at pH 4.00, 7.00 and 10.00.
```

**Response:**

### Uncertainty Budget: pH Measurement in Water Samples

**Method:** Potentiometric pH measurement per ISO 10523
**Equipment:** Metrohm 913 pH meter + combined glass electrode
**Calibration:** 3-point (pH 4.00, 7.00, 10.00)

#### Uncertainty Sources (Ishikawa diagram)

```
                    ┌─ Buffer CRM uncertainty
    Calibration ────┤
                    └─ Calibration curve fitting (residuals)

                    ┌─ Repeatability (Type A)
    Measurement ────┤
                    └─ Resolution of instrument

                    ┌─ Temperature effect on electrode
    Temperature ────┤
                    └─ Temperature compensation uncertainty

    Sample ─────────── Matrix effects / junction potential
```

#### Component Quantification

| Source | Type | Value | Distribution | Standard uncertainty u(x) | Sensitivity | u(pH) |
|--------|------|-------|-------------|--------------------------|-------------|-------|
| **Buffer CRM** | B | ±0.02 pH (from certificate) | Rectangular | 0.02/√3 = 0.0115 | 1 | 0.0115 |
| **Calibration residuals** | B | Max residual 0.015 pH | Rectangular | 0.015/√3 = 0.0087 | 1 | 0.0087 |
| **Repeatability** | A | SD from 10 measurements = 0.018 pH | Normal | 0.018/√3 = 0.0104 | 1 | 0.0104 |
| **Resolution** | B | 0.01 pH | Rectangular | 0.01/(2√3) = 0.0029 | 1 | 0.0029 |
| **Temperature** | B | ±1°C variation, ~0.003 pH/°C | Rectangular | (1×0.003)/√3 = 0.0017 | 1 | 0.0017 |
| **Junction potential** | B | Estimated ±0.02 pH for clean water | Rectangular | 0.02/√3 = 0.0115 | 1 | 0.0115 |

#### Combined and Expanded Uncertainty

**Combined standard uncertainty:**
```
u_c(pH) = √(0.0115² + 0.0087² + 0.0104² + 0.0029² + 0.0017² + 0.0115²)
u_c(pH) = √(0.000132 + 0.000076 + 0.000108 + 0.000008 + 0.000003 + 0.000132)
u_c(pH) = √(0.000459)
u_c(pH) = 0.021 pH
```

**Expanded uncertainty (k=2, ~95% confidence):**
```
U(pH) = 2 × 0.021 = 0.04 pH
```

#### Reporting
Report results as: **pH = X.XX ± 0.04** (k=2, 95% confidence level)

#### Notes
1. The junction potential component is the most difficult to estimate. For clean drinking water, ±0.02 is reasonable. For wastewater or high-ionic-strength samples, this may be larger (±0.05 or more)
2. Repeatability should be determined from your own data — measure a stable sample 10 times under repeatability conditions
3. Review and update this budget annually, or when changing electrode type or buffer supplier
4. Buffer uncertainty comes from the CRM certificate — verify your supplier provides ISO 17034 certified buffers

---

## 5. Nonconforming Work Procedure

**Prompt:**
```
/iso-17025 Write a procedure for handling nonconforming work
(clause 7.10) for a chemical testing laboratory.
```

**Response:**

## PROCEDURE: Handling of Nonconforming Work

| | |
|---|---|
| **Document No.:** | QP-710-01 |
| **Version:** | 1.0 |
| **Effective Date:** | [DATE] |
| **Reference:** | ISO/IEC 17025:2017, clause 7.10 |
| **Approved by:** | [Quality Manager] |

### 1. Purpose
To define the process for identifying, evaluating, and managing work that does not conform to laboratory procedures, client requirements, or agreed specifications.

### 2. Scope
Applies to all testing activities within the laboratory's scope of accreditation, including sampling, sample handling, analysis, data processing, and reporting.

### 3. References
- ISO/IEC 17025:2017, clause 7.10
- QP-870-01 Corrective Actions Procedure
- QP-780-01 Reporting Procedure

### 4. Responsibilities

| Role | Responsibility |
|------|---------------|
| **All personnel** | Identify and report nonconforming work immediately |
| **Section Leader** | Initial evaluation, immediate actions, risk assessment |
| **Quality Manager** | Review, approve disposition, determine if client notification needed |
| **Laboratory Director** | Authorize resumption of work, approve report withdrawal/amendment |

### 5. Procedure

#### 5.1 Identification of Nonconforming Work
Nonconforming work may be identified through:
- QC results outside acceptance limits (control charts, blanks, duplicates, CRM recovery)
- Unsatisfactory PT/ILC results
- Equipment malfunction or overdue calibration
- Environmental conditions outside specified limits
- Client complaints
- Internal audit findings
- Personnel error (e.g., incorrect method, sample mix-up)
- Deviation from documented procedures

#### 5.2 Immediate Actions
When nonconforming work is identified:

1. **STOP** — Halt affected work immediately
2. **RECORD** — Document the nonconformity on Form F-710-01 (Nonconformity Report), including:
   - Date and time of discovery
   - Description of the nonconformity
   - Affected samples/reports (identification numbers)
   - Person who identified the issue
3. **ISOLATE** — Segregate affected samples, data, or equipment
4. **NOTIFY** — Inform Section Leader and Quality Manager immediately

#### 5.3 Risk Evaluation
The Section Leader shall evaluate:

| Question | Action if YES |
|----------|--------------|
| Could incorrect results have been reported to clients? | Proceed to 5.4 (client notification) |
| Could other samples/tests be affected? | Extend investigation to all potentially affected work |
| Is the nonconformity recurring? | Initiate corrective action per QP-870-01 |
| Does this affect the validity of previous results? | Review results back to last known good QC point |

#### 5.4 Client Notification
The Quality Manager shall notify the client when:
- Results have already been reported and may be invalid
- The nonconformity affects the client's use of results
- Contractual requirements mandate notification

Notification shall be documented and include:
- Which results are affected
- Nature of the nonconformity
- Proposed resolution (re-test, report amendment, report withdrawal)

#### 5.5 Disposition
The Quality Manager determines one of the following:

| Disposition | When Used |
|-------------|-----------|
| **Accept as-is** | Risk evaluation shows results are still valid (e.g., minor deviation within uncertainty) |
| **Re-test** | Sufficient sample remains, re-analysis is feasible |
| **Amend report** | Results already reported require correction |
| **Withdraw report** | Results are unreliable and cannot be corrected |
| **Reject sample** | Sample integrity compromised; re-sampling required |

#### 5.6 Resumption of Work
Work may resume only when:
- Root cause is understood
- Immediate correction is implemented
- Quality Manager has authorized resumption
- Authorization is documented on the Nonconformity Report

#### 5.7 Corrective Actions
If the evaluation indicates the nonconformity could recur (7.10.3), initiate corrective action per QP-870-01, including:
- Root cause analysis (5 Whys, fishbone diagram)
- Implementation of corrective measures
- Verification of effectiveness

### 6. Records
- Form F-710-01: Nonconformity Report
- Nonconformity Log (register of all NCRs)
- Client notification records
- Evidence of corrective actions (linked to QP-870-01)

Retention: Minimum 5 years (or as required by accreditation body/regulations)

### 7. Flowchart

```
  Nonconformity identified
          │
          ▼
  STOP affected work
          │
          ▼
  Record on F-710-01
          │
          ▼
  Risk evaluation ──── Could client be affected? ──YES──► Notify client
          │                                                    │
          ▼                                                    ▼
  Determine disposition ◄──────────────────────────────────────┘
          │
          ├── Accept as-is
          ├── Re-test
          ├── Amend report
          ├── Withdraw report
          └── Reject sample
          │
          ▼
  Could it recur? ──YES──► Initiate corrective action (QP-870-01)
          │
          ▼
  Authorize resumption
          │
          ▼
  Close NCR
```

---

## 6. LIMS Compliance Requirements

**Prompt:**
```
/iso-17025 We're evaluating LIMS vendors. What specific requirements
does ISO 17025 clause 7.11 place on laboratory software?
Give me a checklist I can send to vendors.
```

**Response:**

### LIMS Vendor Evaluation Checklist — ISO/IEC 17025:2017 Clause 7.11

Send this to vendors and ask them to demonstrate each capability.

#### 1. Validation (7.11.2)

| # | Requirement | Vendor Response |
|---|-------------|----------------|
| 1.1 | System can be validated before deployment (IQ/OQ/PQ documentation available) | |
| 1.2 | Validation documentation provided (test protocols, expected results, evidence) | |
| 1.3 | Interface validation tools available (instrument interfaces, imports/exports) | |
| 1.4 | All configuration changes can be validated before going live | |
| 1.5 | Change log tracks all system configuration changes with who/when/what | |
| 1.6 | Vendor provides release notes and regression test results for updates | |

#### 2. Access Control (7.11.3a)

| # | Requirement | Vendor Response |
|---|-------------|----------------|
| 2.1 | Role-based access control (define permissions per user role) | |
| 2.2 | Individual user accounts (no shared logins) | |
| 2.3 | Password policy enforcement (complexity, expiration, lockout) | |
| 2.4 | Ability to restrict access to specific functions (e.g., only authorized personnel can approve results) | |
| 2.5 | Session timeout after inactivity | |
| 2.6 | Access control for data modification (who can edit what, and when) | |

#### 3. Data Integrity & Audit Trail (7.11.3b, 7.11.3d)

| # | Requirement | Vendor Response |
|---|-------------|----------------|
| 3.1 | Complete audit trail: who changed what, when, old value → new value | |
| 3.2 | Audit trail cannot be modified or deleted (including by admin) | |
| 3.3 | Original data preserved — changes tracked as amendments, not overwrites | |
| 3.4 | Electronic signatures with meaning (e.g., "reviewed by", "approved by") | |
| 3.5 | Reason for change required when modifying results | |
| 3.6 | ALCOA+ principles supported (Attributable, Legible, Contemporaneous, Original, Accurate) | |

#### 4. Backup & Recovery (7.11.3b)

| # | Requirement | Vendor Response |
|---|-------------|----------------|
| 4.1 | Automated backup capability (scheduled, verified) | |
| 4.2 | Disaster recovery procedure documented and tested | |
| 4.3 | Point-in-time recovery possible | |
| 4.4 | Backup integrity verification (checksums, restore tests) | |
| 4.5 | Data export capability in open format (for long-term archiving) | |

#### 5. System Failure Handling (7.11.3e)

| # | Requirement | Vendor Response |
|---|-------------|----------------|
| 5.1 | System failure logging and alerting | |
| 5.2 | Data protection during unexpected shutdown (transaction integrity) | |
| 5.3 | Automatic recovery after system failure | |
| 5.4 | Uptime SLA and support response times | |

#### 6. Calculations & Data Transfer (7.11.6)

| # | Requirement | Vendor Response |
|---|-------------|----------------|
| 6.1 | Built-in calculation engine with formula transparency | |
| 6.2 | Calculation verification tools (ability to check against manual calculation) | |
| 6.3 | Instrument data import without manual transcription | |
| 6.4 | Data transfer validation (checksums, record counts) | |
| 6.5 | Rounding rules configurable and documented | |

#### 7. Additional 17025-Specific Features

| # | Feature | Vendor Response |
|---|---------|----------------|
| 7.1 | Measurement uncertainty storage and reporting | |
| 7.2 | Conformity statement generation with decision rules | |
| 7.3 | QC chart management (control charts, trend analysis) | |
| 7.4 | Equipment calibration tracking and alerts | |
| 7.5 | Sample chain of custody tracking | |
| 7.6 | Report generation meeting 7.8.2.1 requirements | |
| 7.7 | Document control integration | |
| 7.8 | Training/competence record management | |
| 7.9 | Nonconforming work workflow | |
| 7.10 | PT/ILC result tracking | |

#### Scoring Guide
For each item, score the vendor:
- **2** = Fully meets requirement out of the box
- **1** = Meets with configuration/customization
- **0** = Does not meet / not available
- **N/A** = Not applicable to your laboratory

**Minimum acceptable score:** Items 1.1, 2.1, 3.1, 3.2, 4.1, 5.2, 6.1, 6.3 are mandatory (score must be 1 or 2).

---

## 7. Decision Rules for Conformity Statements

**Prompt:**
```
/iso-17025 Explain decision rules for conformity statements
per clause 7.8.6. When should we use simple acceptance,
guard banding, or other approaches? Give practical examples.
```

**Response:**

### Decision Rules for Conformity Statements (7.8.6)

Per clause 7.8.6, whenever you state that a result "passes" or "fails" a specification, you **must** document the decision rule used and the associated risk level.

#### What is a Decision Rule?

A decision rule describes **how measurement uncertainty is accounted for** when making a pass/fail statement. The key question: *What do we do when the result is close to the specification limit?*

#### The Four Common Approaches

**1. Simple Acceptance (no guard band)**
```
    FAIL    │    PASS
            │
  ──────────┼──────────
            Limit
```
- **Rule:** Result ≤ limit = PASS, Result > limit = FAIL
- **Uncertainty:** Acknowledged but not used in the decision
- **Risk:** ~50% probability of false acceptance when result equals the limit
- **When to use:** When the client/regulation explicitly states this rule, or when the consequence of false acceptance is low
- **Example:** EU drinking water directive — limits are compared directly to the measured value

**2. Guard Band — Shared Risk (W₁ rule, ILAC-G8)**
```
    FAIL    │  Guard  │    PASS
            │  band   │
  ──────────┼─────────┼──────────
         Limit-U    Limit
```
- **Rule:** Result ≤ (limit - U) = PASS. Result > limit = FAIL. Between = "Not possible to state conformity"
- **Risk:** False acceptance probability < 2.5% for PASS statements
- **When to use:** Default approach recommended by ILAC-G8. Good for most testing laboratories
- **Example:** Testing tensile strength of steel. Spec ≥ 400 MPa, U = ±8 MPa. Result of 395 MPa → cannot state conformity (within guard band 392-400)

**3. Guard Band — Consumer Risk (stringent)**
```
    FAIL    │    PASS
            │
  ──────────┼──────────
         Limit-U
```
- **Rule:** PASS only when result + U ≤ limit (i.e., entire uncertainty interval is within spec)
- **Risk:** Virtually zero false acceptance, but higher false rejection
- **When to use:** Safety-critical measurements (pharmaceutical, medical devices, structural integrity)
- **Example:** Pharmaceutical impurity limit ≤ 0.1%. U = ±0.01%. Result must be ≤ 0.09% to declare PASS

**4. Guard Band — Producer Risk (lenient)**
```
    FAIL    │    PASS
            │
  ──────────┼──────────
         Limit+U
```
- **Rule:** FAIL only when result - U > limit
- **Risk:** Higher false acceptance, but lower false rejection
- **When to use:** When false rejection is more costly than false acceptance
- **Example:** Rare/expensive product testing where re-testing is destructive

#### Practical Decision Matrix

| Situation | Recommended Rule | Rationale |
|-----------|-----------------|-----------|
| Regulatory limit, safety-critical | Guard band (consumer risk) | Public safety priority |
| Regulatory limit, non-safety | Simple acceptance or ILAC-G8 W₁ | Regulations often assume simple acceptance |
| Client specification, standard | ILAC-G8 W₁ (shared risk) | Balanced approach, widely accepted |
| Client specifies "no uncertainty" | Simple acceptance | Document client's explicit request |
| Internal QC limits | Simple acceptance | Internal use, consequences manageable |

#### How to Document (required by 7.8.6)

Your laboratory must have a documented procedure that:
1. **Lists all decision rules** used for different test types
2. **Defines the risk level** for each rule
3. **States how the rule is applied** (formula or description)
4. **Specifies when each rule is used** (default, client-specific, regulatory)
5. **Appears on reports** — the decision rule must be identified in or referenced from the report

#### Example Report Statement
*"Conformity assessment performed using ILAC-G8:09/2019 with guard band at expanded uncertainty level (k=2, 95%). Results marked 'Pass' have ≤2.5% probability of false acceptance."*

---

## 8. Internal Audit Plan — 12-Month Cycle

**Prompt:**
```
/iso-17025 Generate an internal audit plan for our calibration
laboratory covering all clauses over a 12-month cycle.
We have 3 qualified auditors.
```

**Response:**

### Internal Audit Program — 12-Month Cycle

**Laboratory:** [Name] — Calibration Laboratory
**Period:** [Year]
**Auditors:** A1, A2, A3 (ensure no auditor audits their own work area)

#### Audit Schedule

| Month | Clauses | Scope/Focus | Lead Auditor | Duration |
|-------|---------|-------------|--------------|----------|
| **Jan** | 4.1, 4.2, 5 | Impartiality risk assessment (annual review), confidentiality agreements, structural requirements, org chart | A1 | 1 day |
| **Feb** | 6.2 | Personnel: competence records, training plan, authorizations, monitoring. Interview 3 staff members | A2 | 1 day |
| **Mar** | 6.4, 6.5 | Equipment: calibration program, records, labels, intermediate checks. Metrological traceability chain | A3 | 1.5 days |
| **Apr** | 7.2 | Methods: verification/validation records, current versions, method register. Select 3 methods for deep review | A1 | 1 day |
| **May** | 7.6, 7.7 | Measurement uncertainty budgets (review 3), QC program, control charts, PT results and actions | A2 | 1.5 days |
| **Jun** | 7.8 | Reporting: review 10 certificates against 7.8.4 requirements, conformity statements, decision rules | A3 | 1 day |
| **Jul** | 7.1, 7.4, 7.5 | Contract review records, item handling, technical records completeness | A1 | 1 day |
| **Aug** | 6.3, 6.6 | Facilities/environment (monitoring records), external providers (evaluations, approved supplier list) | A2 | 0.5 day |
| **Sep** | 7.9, 7.10 | Complaints register, nonconforming work records, risk evaluations, corrective action links | A3 | 0.5 day |
| **Oct** | 7.11 | LIMS/software: validation records, access controls, backup testing, audit trail, data integrity | A1 | 1 day |
| **Nov** | 8.2-8.4, 8.5, 8.6 | QMS documentation, document control, record control, risk register, improvement actions | A2 | 1 day |
| **Dec** | 8.7, 8.8 | Corrective actions (closure, effectiveness), review of this year's audit findings | A3 | 0.5 day |

**Note:** Clause 8.9 (Management Review) is covered by the review itself, scheduled for January of the following year. The audit program and its results feed into the management review as required input (8.9.2e).

#### Auditor Assignment Rules
- No auditor audits their own work area or processes they directly manage
- Each auditor leads at least 3 and no more than 5 audits per year
- Rotation: auditors do not audit the same clause two years in a row

#### For Each Audit, Produce:
1. **Audit plan** (scope, criteria, schedule, methods)
2. **Checklist** (specific questions/evidence to examine)
3. **Audit report** with:
   - Findings classified as: Major NC / Minor NC / Observation / Opportunity for Improvement
   - Objective evidence for each finding
   - Due dates for corrective actions
4. **Follow-up** — verify corrective action effectiveness within 30 days
