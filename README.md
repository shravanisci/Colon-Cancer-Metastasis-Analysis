# Transcriptomic Reprogramming During Colorectal Cancer Liver Metastasis

## Overview

Colorectal cancer (CRC) is one of the leading causes of cancer-related mortality worldwide. A major contributor to patient mortality is metastasis, particularly to the liver, which occurs in nearly 50% of CRC patients during disease progression.

This project investigates how colorectal cancer cells adapt to the liver microenvironment by comparing transcriptomic profiles between primary colorectal tumors and liver metastatic lesions.

---

## Research Question

How do colorectal cancer cells alter their transcriptional programs to survive and colonize the liver microenvironment?

---

## Dataset

**GEO Dataset:** GSE50760

Comparison groups:

- Primary colorectal cancer
- Liver metastatic colorectal cancer

---

## Workflow

GSE50760 RNA-seq Data

↓

Expression Matrix Processing

↓

Differential Expression Analysis (limma-voom)

↓

PCA + Volcano Plot + Heatmap

↓

Over-Representation Analysis (ORA)

↓

Gene Set Enrichment Analysis (GSEA)

↓

Biological Interpretation

---

## Methods

- R + Bioconductor
- limma-voom differential expression analysis
- Principal Component Analysis (PCA)
- Volcano plot visualization
- Hierarchical clustering heatmaps
- Over-Representation Analysis (ORA)
- Gene Set Enrichment Analysis (GSEA)

---

## Key Findings

### 1. Distinct Transcriptomic States

PCA revealed a clear separation between primary colorectal tumors and liver metastatic samples, indicating substantial transcriptomic reprogramming during metastasis.

### 2. Extensive Differential Gene Expression

Hundreds of genes were significantly dysregulated between primary and metastatic lesions, suggesting large-scale adaptation to a new tissue environment.

### 3. Metabolic Rewiring

ORA and GSEA consistently identified enrichment of pathways associated with:

- Fatty acid metabolism
- Glycolysis / gluconeogenesis
- Drug metabolism
- Xenobiotic metabolism
- PPAR signaling

### 4. Extracellular Remodeling

Enrichment of extracellular matrix and extracellular space-associated pathways suggests active remodeling of the metastatic niche.

### 5. Complement and Coagulation Signatures

Complement and coagulation pathways emerged among the strongest enriched terms, highlighting potential interactions between metastatic cancer cells and the liver microenvironment.

---

## Biological Interpretation

Rather than simply spreading to a new organ, metastatic colorectal cancer cells appear to undergo extensive transcriptional reprogramming that may improve their fitness within the liver.

These findings support the hypothesis that metastasis is not only a process of migration but also one of adaptation.

---

## Repository Structure

```text
Colon-Cancer-Metastasis-Analysis/
│
├── notebook/
│   └── CRC_Metastasis_Transcriptomics.ipynb
│
├── figures/
│   ├── pcaplot_gse50760.png
│   ├── volcanoplot_gse50760.png
│   ├── clustered_heatmap_gse50760.png
│   ├── ora_vs_gsea.png
│   └── ...
│
└── README.md
```

---

## Future Directions

- Survival analysis of candidate genes
- Validation using TCGA colorectal cancer datasets
- Investigation of metastasis-associated biomarkers
- Integration with proteomic and clinical datasets

---

## Author

**Shravani BS Bollapragada**

BSc Biochemistry, Genetics & Biotechnology

Computational Biology | Transcriptomics | Cancer Biology
