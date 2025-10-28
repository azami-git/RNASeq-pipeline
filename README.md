# 🧬 RNA-Seq Pipeline: From FASTQ to Counts

This repository provides a complete, step-by-step Bash pipeline to process RNA-Seq data **from raw FASTQ reads to gene-level counts** using widely adopted bioinformatics tools: **FastQC**, **Trimmomatic**, **HISAT2**, **SAMtools**, and **featureCounts**.

The pipeline is simple, reproducible, and can be run entirely on macOS or Linux.

---

## ⚙️ **Pipeline Overview**

| Step | Tool | Description |
|------|------|--------------|
| 1 | **FastQC** | Quality check of raw FASTQ reads |
| 2 | **Trimmomatic** | Trims poor-quality bases and adapters |
| 3 | **HISAT2** | Aligns reads to a reference genome |
| 4 | **SAMtools** | Sorts and processes alignment files |
| 5 | **featureCounts** | Counts reads mapped to annotated genes |

---

**Download the example FASTQ file:**
   📂 [Download Demo Data (Google Drive)](https://drive.google.com/file/d/1DGHjbhcRy_zTm6H9C_AUpkzBML-JhtA3/view?usp=sharing)

