# ISO/IEC 17025:2017 — Method Validation Guide

## When Validation is Required (7.2.2.1)

Validation is required for:
- Non-standardized methods
- Laboratory-developed methods
- Standardized methods used outside their intended scope
- Modified standardized methods (amplifications/modifications)

Verification (not full validation) is sufficient for:
- Standardized methods used within their scope, to confirm the laboratory can properly perform the method

## Validation Parameters (7.2.2.3)

### Required Characteristics to Evaluate

| Parameter | Description | When Required |
|-----------|-------------|---------------|
| **Selectivity/Specificity** | Ability to measure analyte without interference from matrix components | Always |
| **Linearity** | Range over which response is proportional to concentration | Quantitative methods |
| **Working Range** | Interval of analyte concentrations for which method provides acceptable results | Quantitative methods |
| **Accuracy (Trueness)** | Closeness of mean result to true/accepted value (bias/recovery) | Always for quantitative |
| **Precision — Repeatability** | Variability under same conditions (same operator, equipment, short time) | Always |
| **Precision — Intermediate Precision** | Variability within laboratory (different operators, equipment, days) | Recommended |
| **Precision — Reproducibility** | Variability between laboratories (from interlaboratory studies) | When available |
| **Limit of Detection (LOD)** | Lowest amount that can be detected (not necessarily quantified) | When results near LOD expected |
| **Limit of Quantification (LOQ)** | Lowest amount that can be quantified with acceptable precision/accuracy | Trace analysis methods |
| **Robustness** | Resistance to small deliberate variations in method parameters | Recommended |
| **Measurement Uncertainty** | Parameter characterizing dispersion of values attributable to measurand | Always |
| **Sensitivity** | Change in response per unit change in concentration | When comparing methods |
| **Matrix Effects** | Influence of sample matrix on measurement | When different matrices analyzed |

### Microbiological Method Validation — Specific Parameters

| Parameter | Description |
|-----------|-------------|
| **Relative trueness** | Comparison with reference method using naturally contaminated or spiked samples |
| **Relative sensitivity** | Ratio of positives detected by alternative vs reference method |
| **Relative specificity** | Ratio of negatives confirmed by alternative vs reference method |
| **Relative accuracy** | Degree of agreement between alternative and reference method |
| **Relative LOD** | Lowest contamination level reliably detected |
| **Inclusivity** | Ability to detect target organisms from diverse sources |
| **Exclusivity** | Absence of false positives from non-target organisms |

## Validation Plan Structure

```
1. Objective
   - What method is being validated
   - Intended use/scope (analytes, matrices, concentration ranges)
   - Reference to standard or procedure

2. Validation Parameters
   - Which parameters will be evaluated (justified based on intended use)
   - Acceptance criteria for each parameter (defined BEFORE validation)

3. Experimental Design
   - Number of measurements/replicates
   - Concentration levels
   - Matrices to be tested
   - Reference materials/standards to be used
   - Statistical methods for data evaluation

4. Resources Required
   - Personnel (with competence requirements)
   - Equipment and reagents
   - Reference materials/standards
   - Timeline

5. Acceptance Criteria
   - Defined for each parameter BEFORE starting experiments
   - Based on: client requirements, regulatory limits, method performance goals
```

## Validation Report Structure (7.2.2.4)

The validation report shall contain:

1. **Method identification** — title, version, reference
2. **Scope** — analyte(s), matrix/matrices, range
3. **Validation procedure** — experimental design, materials used
4. **Specification of requirements** — acceptance criteria
5. **Results for each parameter** — data, statistical analysis
6. **Fitness-for-purpose statement** — conclusion on whether method meets requirements
7. **Any limitations or conditions** identified during validation
8. **Approval** — date, responsible person, authorization

## Common Acceptance Criteria Examples

### Chemical Testing
| Parameter | Typical Criteria |
|-----------|-----------------|
| Recovery | 80-120% (varies by concentration and matrix) |
| Repeatability (RSD) | <5-10% (depending on concentration level) |
| Intermediate precision (RSD) | <10-15% |
| Linearity (R^2) | >0.995 (typically >0.999) |
| LOD | < 1/10 of regulatory limit |
| LOQ | < 1/3 of regulatory limit |

### Microbiological Testing
| Parameter | Typical Criteria |
|-----------|-----------------|
| Relative accuracy | >90% agreement with reference method |
| Relative sensitivity | >90% |
| Relative specificity | >90% |
| False positive rate | <5% |
| False negative rate | <5% |

## Important Notes

- Validation shall be as extensive as necessary to meet the needs of the intended application (7.2.2.1)
- When changes are made to a validated method, the influence shall be determined and if significant, a new validation shall be conducted (7.2.2.2)
- Validation results, including fitness-for-purpose statement, shall be recorded and retained (7.2.2.4)
- Acceptance criteria shall be defined BEFORE validation, not after seeing results
