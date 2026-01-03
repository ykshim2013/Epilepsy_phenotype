---
layout: default
title: Home
---

# Epilepsy Gene Variant Analysis

Comprehensive variant analysis reports for five epilepsy-related genes based on ClinVar database and published literature.

**Date Generated:** January 2, 2026

---

## Gene Reports

| Gene | P | LP | P/LP* | Unique P/LP | Total ClinVar | Publications | Reported Patients | Key Phenotype | Report |
|------|---|----|----|-------------|---------------|--------------|-------------------|---------------|--------|
| **SCN2A** | 437 | 361 | 56 | **742** | 2,978 | >150 | >400 | DEE11, BFNIS | [View Report](SCN2A_variant_analysis.md) |
| **EEF1A2** | 69 | 45 | 6 | **108** | 728 | ~30 | ~68 | DEE33 | [View Report](EEF1A2_variant_analysis.md) |
| **KCNQ2** | 621 | 332 | 88 | **865** | 2,493 | >200 | >500 | BFNS, KCNQ2-DEE | [View Report](KCNQ2_variant_analysis.md) |
| **SYNGAP1** | 323 | 129 | 20 | **432** | 1,833 | >100 | ~246 | MRD5, SYNGAP1-DEE | [View Report](SYNGAP1_variant_analysis.md) |
| **CDKL5** | 763 | 306 | 48 | **1,021** | 2,407 | >300 | >1,000 | CDD, DEE2 | [View Report](CDKL5_variant_analysis.md) |

*P/LP = Variants with both Pathogenic and Likely Pathogenic submissions. Unique P/LP = P + LP - P/LP (to avoid double-counting).

---

## Report Structure

Each report contains:

### 1. 전체 (Overall Summary)
- Total variant count
- Total publications
- Total reported patients
- Variant-to-patient frequency distribution

### 2. ClinVar P/LP
- Pathogenic and Likely Pathogenic variant counts
- Associated publications
- Patient counts
- Recurrent variant examples

### 3. Non-P/LP Variants (전체에서 ClinVar P/LP를 제외한)
- ClinVar VUS/Benign/Likely Benign/Conflicting Classifications
- Literature-reported variants NOT in ClinVar
- Distribution by ClinVar classification category

### 4. Korean Patient Data
- Korean-specific publications
- Reported variants in Korean population

### 5. Phenotype Review
- Seizure onset age
- Responsive anti-seizure medications (ASM)
- Syndrome diagnosis / gene-specific classification

---

## Quick Reference: Treatment by Gene

| Gene | First-Line ASM | Avoid | Special Notes |
|------|----------------|-------|---------------|
| **SCN2A** | Na+ channel blockers (if onset <3mo) | Na+ blockers if onset >1yr | GOF vs LOF determines treatment |
| **EEF1A2** | Variable | - | Generally drug-resistant |
| **KCNQ2** | Carbamazepine, Phenytoin | - | ~80% respond to Na+ blockers |
| **SYNGAP1** | Valproate, Lamotrigine | - | 63% drug-resistant; CBD promising |
| **CDKL5** | Vigabatrin | - | Only 24% maintain response at 12mo |

---

## Data Sources

- [ClinVar Database](https://www.ncbi.nlm.nih.gov/clinvar/)
- [PubMed Literature](https://pubmed.ncbi.nlm.nih.gov/)
- [GeneReviews](https://www.ncbi.nlm.nih.gov/books/NBK1116/)

---

## Contact

For questions or updates, please open an issue on the [GitHub repository](https://github.com/ykshim2013/Epilepsy_phenotype).

---

*Data accessed January 2026. Variant counts and classifications are subject to change as databases are updated.*
