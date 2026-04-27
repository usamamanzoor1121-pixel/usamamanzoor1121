<div align="center">

# 🧬 Usama Manzoor
### Bioinformatician · Computational Genomics · NGS Data Analysis

[![Email](https://img.shields.io/badge/Email-usama.manzoor1121%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:usama.manzoor1121@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-usamamanzoor1121--pixel-181717?style=flat-square&logo=github)](https://github.com/usamamanzoor1121-pixel)
[![Location](https://img.shields.io/badge/Karachi%2C%20Pakistan-0078D4?style=flat-square&logo=googlemaps&logoColor=white)]()
[![ESHG](https://img.shields.io/badge/Member-ESHG-6A0DAD?style=flat-square)](https://www.eshg.org/)
[![ISCB](https://img.shields.io/badge/Member-ISCB-1E90FF?style=flat-square)](https://www.iscb.org/)

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=usamamanzoor1121-pixel&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

</div>

---

## 👨‍🔬 About Me

Results-driven Bioinformatician with **5+ years of progressive experience** in clinical genomics, NGS data analysis, and bioinformatics pipeline development. Currently operating NIPT bioinformatics pipelines at JSMU Diagnostic Laboratory, collaborating with geneticists, molecular pathologists, and lab scientists to deliver clinically actionable genomic insights.

My work spans **multi-omics integration**, **variant analysis (SNPs, Indels, CNVs, SVs)**, **ML/DL-driven genomic discovery**, and **bacterial genomics** — from raw FASTQ reads to publication-ready results.

---

## 🔬 Featured Research Pipelines

---

### 🫁 [LUAD Multi-Omics & ML Pipeline](https://github.com/usamamanzoor1121-pixel/luad-multiomics-pipeline)
> **Lung Adenocarcinoma · TCGA-LUAD · RNA-seq + WES + Methylation + ML/DL**

Comprehensive multi-omics study of TCGA-LUAD integrating RNA-seq (513 tumour / 59 normal), whole-exome somatic mutations, and DNA methylation (Illumina 450k) to identify master regulatory genes and clinically actionable molecular targets.

**Key Highlights:**
- 50 upregulated / 30 downregulated genes from 12,500 expressed (DESeq2; padj<0.05, |log2FC|>1.5)
- TP53 as top hub gene (degree=318, MCC Rank #1) via STRING PPI + CytoHubba
- 23,400 hypermethylated CpGs including RASSF1A, CDKN2A, MLH1
- 5 ML/DL models on 43-feature matrix (38 DEGs + 5 mutation statuses); 5-fold CV + 80:20 split

`Python` `R` `DESeq2` `GATK` `STRING` `Cytoscape` `Scikit-Learn` `TensorFlow` `Illumina 450k` `TCGA`

---

### 🧠 [AD × T2DM Cross-Disease Multi-Omics Pipeline](https://github.com/usamamanzoor1121-pixel/ad-t2dm-crossdisease-pipeline)
> **Alzheimer's Disease · Type 2 Diabetes · Drug Repurposing · Novel BDS Score**

The **first integrated multi-omics pipeline applied simultaneously to AD and T2DM**, identifying shared druggable pathways across 329 AD + 188 control samples (ROSMAP/GEO) and n=675 T2DM multi-tissue RNA-seq samples (GTEx/GEO).

**Key Highlights:**
- 3 AD molecular stages with distinct survival profiles (log-rank p<0.001)
- 🆕 Novel **β-Cell Dedifferentiation Score (BDS)** correlating with HbA1c (Spearman r=0.74)
- 6 shared cross-disease pathways; IRS1 & GSK3β as dual therapeutic nodes
- 8 drug repurposing candidates including semaglutide (EVOKE Phase III) and metformin (MILES AD trial)

`Python` `R` `DESeq2` `K-Means` `RF` `SVM` `GBM` `MLP` `LASSO` `HMDB` `GTEx` `GWAS` `ROSMAP`

---

### 🤰 [NIPT Bioinformatics Pipeline](https://github.com/usamamanzoor1121-pixel/nipt-bioinformatics-pipeline)
> **Non-Invasive Prenatal Testing · Clinical Genomics · Aneuploidy Detection**

End-to-end clinical NIPT pipeline currently deployed in production at JSMU Diagnostic Laboratory. Handles alignment, fetal fraction estimation, CNV calling, and aneuploidy detection for chromosomes 13, 18, 21, X, and Y.

**Key Highlights:**
- Full clinical-grade pipeline from FASTQ → aneuploidy report
- Integrates BWA, Samtools, Picard for alignment and QC
- Fetal fraction estimation and Z-score based aneuploidy calling
- Rigorous QC metrics on sequencing run data (FASTQ, BAM/CRAM)

`BWA` `Bowtie2` `Samtools` `Picard` `Python` `Bash` `R` `Illumina` `FASTQ/BAM/VCF`

---

### 🦠 [Hypervirulent *K. pneumoniae* Pakistan — Bacterial Genomics Pipeline](https://github.com/usamamanzoor1121-pixel/kp-pakistan-hypervirulence)
> **Bacterial Genomics · Molecular Epidemiology · AMR · Pan-Genome · MLflow · DVC**

Comprehensive molecular epidemiology pipeline for hypervirulent *Klebsiella pneumoniae* (hvKP) from Pakistan, adapted from Li et al. 2024. Includes pan-genome analysis with ROARY as an additional component beyond the reference methodology.

**Key Highlights:**
- Multi-database acquisition: BV-BRC + NCBI SRA + Pathogen Detection + ENA (orchestrated with Apache Airflow)
- Genotyping with Kleborate v3.0.8; hvKP classification (iucA + rmpA/rmpA2 molecular definition)
- Core-genome phylogeny: Parsnp v1.2 → FastTree v2.1 (GTR+GAMMA) → iTOL
- cgMLST clustering: chewBBACA v3.3.9 (2,358-gene RIDOM scheme) → GrapeTree MSTv2
- Plasmid analysis: MOB-Suite v3.19 → Mash v2.2 → Louvain community detection
- 🆕 **Pan-genome analysis with ROARY** for accessory genome characterization
- Full ML pipeline (RF, XGBoost+Optuna, LightGBM, SHAP) + MLflow + DVC reproducibility

`Python` `R` `Kleborate` `ROARY` `Parsnp` `FastTree` `chewBBACA` `MOB-Suite` `Mash` `MLflow` `DVC` `Airflow`

---

## 🛠️ Technical Skills

| Domain | Tools & Technologies |
|---|---|
| **NGS Platforms** | Illumina (SBS), PacBio SMRT, Oxford Nanopore, Ion Torrent |
| **Bioinformatics** | BWA, Bowtie2, Samtools, Picard, GATK, FastQC, CNV tools |
| **Data Formats** | FASTQ · SAM · BAM · CRAM · VCF |
| **Variant Analysis** | SNPs, SNVs, Indels, CNVs, Structural Variants |
| **Genomic Databases** | NCBI, Ensembl, UCSC, ClinVar, LOVD, 1000 Genomes, KEGG |
| **Programming** | Python (Pandas, NumPy, Scikit-Learn) · R · Bash/Shell · Linux |
| **ML / DL** | Random Forest, XGBoost, LightGBM, SVM, MLP, LASSO, SHAP, Optuna |
| **Bacterial Genomics** | Kleborate, ROARY, chewBBACA, MOB-Suite, Prokka, ABRicate, digIS |
| **Reproducibility** | MLflow, DVC, Apache Airflow, Git, Conda |
| **Omics** | RNA-seq DGE, ChIP-seq, DNA Methylation, Pan-genome (PGAP, ROARY) |

---

## 💼 Experience

```
🏥 Bioinformatics Specialist     · JSMU Diagnostic Laboratory, Karachi       [Aug 2025 – Present]
💊 Field & Application Manager   · Oncovanz Pharmaceuticals, Karachi          [Mar 2025 – Aug 2025]
🔬 Medical Technologist          · Liaquat National Hospital, Karachi         [Dec 2020 – Feb 2025]
```

---

## 🎓 Education

- **MS Bioinformatics** — Muhammad Ali Jinnah University, Karachi *(Dec 2023)*
  - Research: *Pan-Genomic Analysis of Enterobacter cloacae*
- **BS Bioinformatics** — Sir Syed University of Engineering & Technology, Karachi *(Feb 2019)*
  - Research: *ML-Based Coronary Artery Heart Disease Prediction*

---

## 🌐 Professional Memberships

[![ESHG](https://img.shields.io/badge/European_Society_of_Human_Genetics-ESHG-6A0DAD?style=flat-square)](https://www.eshg.org/)
[![ISCB](https://img.shields.io/badge/Intl._Society_for_Computational_Biology-ISCB-1E90FF?style=flat-square)](https://www.iscb.org/)
[![deNBI](https://img.shields.io/badge/German_Network_for_Bioinformatics-de.NBI-009900?style=flat-square)](https://www.denbi.de/)
[![ELIXIR](https://img.shields.io/badge/ELIXIR_Life_Science_Community-Europe-FF8C00?style=flat-square)](https://elixir-europe.org/)

---

<div align="center">
<i>"Turning sequencing reads into clinical insights — one pipeline at a time."</i>
</div>
