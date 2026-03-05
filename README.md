# ISO/IEC 17025:2017 — AI Agent Skill

Expert consultant skill for **ISO/IEC 17025:2017** — the international standard for testing and calibration laboratory competence.

Works with **Claude Code**, **Cursor**, **GitHub Copilot**, **Gemini CLI**, **VS Code Copilot**, and [30+ other AI tools](https://agentskills.io) that support the Agent Skills open standard.

## What This Skill Does

Transforms your AI agent into a senior quality management consultant specializing in laboratory accreditation. It provides:

- Deep knowledge of all ISO/IEC 17025:2017 clauses (4-8 + Annexes)
- Audit preparation checklists with common nonconformities
- Gap analysis templates
- Method validation planning guidance
- Measurement uncertainty evaluation support
- Procedure writing templates
- LIMS/software compliance guidance
- Trilingual support (English/Polish/German)

## Installation

### English Version (Quick Install)

```bash
npx skills add cleverlab-ai/iso-17025-skill@iso-17025 -g -y
```

### Wersja polska (Szybka instalacja)

```bash
npx skills add cleverlab-ai/iso-17025-skill@iso-17025-pl -g -y
```

### Deutsche Version (Schnellinstallation)

```bash
npx skills add cleverlab-ai/iso-17025-skill@iso-17025-de -g -y
```

### Manual Install

1. Clone or download this repository
2. Copy the desired language directory to `~/.claude/skills/` (for Claude Code) or `~/.agents/skills/` (universal)

```bash
git clone https://github.com/cleverlab-ai/iso-17025-skill.git

# English
cp -r iso-17025-skill/iso-17025 ~/.claude/skills/

# Polski
cp -r iso-17025-skill/iso-17025-pl ~/.claude/skills/

# Deutsch
cp -r iso-17025-skill/iso-17025-de ~/.claude/skills/
```

### Verify Installation

In Claude Code, type `/iso-17025` (English), `/iso-17025-pl` (Polski) or `/iso-17025-de` (Deutsch) — if the skill appears in autocomplete, it's installed correctly.

## Usage Examples

### 1. Audit Preparation

```
/iso-17025 Prepare me for a PCA surveillance audit next week.
Focus on clause 7 (process requirements).
```

### 2. Gap Analysis

```
/iso-17025 Perform a gap analysis for a small water testing
laboratory that wants to obtain ISO 17025 accreditation.
They currently have no formal QMS.
```

### 3. Write a Procedure

```
/iso-17025 Write a procedure for handling nonconforming work
(clause 7.10) for a chemical testing laboratory.
```

### 4. Method Validation

```
/iso-17025 I need to validate a method for determining heavy
metals in drinking water by ICP-MS. What parameters should
I validate and what acceptance criteria should I use?
```

### 5. Measurement Uncertainty

```
/iso-17025 Help me create an uncertainty budget for pH
measurement in water samples. We use a calibrated pH meter
with buffer solutions at pH 4.00, 7.00 and 10.00.
```

### 6. LIMS Compliance

```
/iso-17025 What requirements does ISO 17025 clause 7.11
place on our laboratory information management system?
We're evaluating a new LIMS vendor.
```

### 7. Internal Audit

```
/iso-17025 Generate an internal audit plan for our
calibration laboratory covering all clauses over
a 12-month cycle.
```

### 8. Management Review

```
/iso-17025 What inputs are required for a management review
according to 8.9.2? Create an agenda template.
```

### 9. Wersja polska — Przygotowanie do audytu

```
/iso-17025-pl Przygotuj checklistę do audytu wewnętrznego
obejmującą wymagania dotyczące personelu (6.2)
i wyposażenia (6.4).
```

### 10. Deutsche Version — Auditvorbereitung

```
/iso-17025-de Bereiten Sie mich auf ein DAkkS-Überwachungsaudit
nächste Woche vor. Schwerpunkt auf Abschnitt 7
(Prozessanforderungen).
```

### 11. Conformity Statements

```
/iso-17025 Explain decision rules for conformity statements
per clause 7.8.6. When should we use simple acceptance,
guard banding, or other approaches?
```

## Skill Contents

```
iso-17025/                                # English version
  SKILL.md                              # Main skill instructions
  references/
    standard-structure.md               # Full standard reference (all clauses)
    audit-checklist.md                  # Detailed audit preparation checklist
    gap-analysis-template.md            # Gap analysis matrix template
    validation-guide.md                 # Method validation planning guide

iso-17025-pl/                             # Wersja polska
  SKILL.md                              # Główne instrukcje skilla
  references/
    struktura-normy.md                  # Pełna struktura normy (wszystkie punkty)
    checklista-audytowa.md              # Szczegółowa checklista audytowa
    szablon-analizy-luk.md              # Szablon macierzy analizy luk
    przewodnik-walidacji.md             # Przewodnik planowania walidacji metod

iso-17025-de/                             # Deutsche Version
  SKILL.md                              # Hauptanweisungen des Skills
  references/
    normenstruktur.md                   # Vollständige Normenstruktur (alle Abschnitte)
    audit-checkliste.md                 # Detaillierte Audit-Vorbereitungscheckliste
    gap-analyse-vorlage.md              # Gap-Analyse-Matrixvorlage
    validierungsleitfaden.md            # Leitfaden zur Methodenvalidierung
```

## Prompt → Response Examples

See full examples with detailed AI responses in all three languages:

- **[English examples](examples/examples-en.md)** — 8 complete prompt/response pairs
- **[Przykłady po polsku](examples/examples-pl.md)** — 8 kompletnych par prompt/odpowiedź
- **[Deutsche Beispiele](examples/examples-de.md)** — 8 vollständige Prompt/Antwort-Paare

### Example topics covered:
1. **Audit preparation** — PCA surveillance audit checklist for clause 7
2. **Gap analysis** — Roadmap for a new 5-person water testing lab
3. **Method validation plan** — Heavy metals (Pb, Cd, As, Hg) by ICP-MS in drinking water
4. **Measurement uncertainty** — Complete uncertainty budget for pH measurement
5. **Procedure writing** — Nonconforming work procedure (clause 7.10) with flowchart
6. **LIMS compliance** — Vendor evaluation checklist for clause 7.11
7. **Decision rules** — Conformity statements with guard banding (clause 7.8.6)
8. **Internal audit plan** — 12-month cycle covering all clauses

## Who Is This For?

- **Quality Managers** preparing for accreditation or surveillance audits
- **Laboratory Directors** building quality management systems
- **Technical Assessors** conducting evaluations
- **Consultants** advising laboratories on ISO 17025 compliance
- **LIMS Developers** building compliant laboratory software
- **Analysts/Technicians** who need to understand quality requirements

## Important Note

This skill provides expert guidance based on the publicly available structure and requirements of ISO/IEC 17025:2017. It does **not** contain the copyrighted full text of the standard. For the official standard text, purchase from [ISO](https://www.iso.org/standard/66912.html) or your national standards body (e.g., [PKN](https://www.pkn.pl) in Poland, [DIN](https://www.din.de) in Germany).

## License

MIT

## Author

**Prym-Soft Sp. z o.o.** — [prym-soft.pl](https://prym-soft.pl)

Developers of [CleverLAB LIMS](https://cleverlab.pl) — laboratory information management system built with ISO/IEC 17025 compliance in mind.
