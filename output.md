---

## 📊 Results and Output Files

After running the pipeline successfully, several key output files will be generated.  
These can be used for downstream analysis in R (using Seurat or Monocle3) or for further QC.

### 🧾 Output Summary

| Step | Output File | Description |
|------|--------------|-------------|
| **FastQC** | `data/demo_fastqc.zip`, `data/demo_fastqc.html` | Quality control reports for raw FASTQ reads |
| **Trimmomatic** | `data/demo_trimmed.fastq` | Trimmed reads with low-quality bases removed |
| **HISAT2** | `HISAT2/demo_trimmed.bam` | Aligned and sorted reads in BAM format |
| **featureCounts** | `quants/demo_featurecounts.txt` | Gene-level read count table (ready for R analysis) |
| **Runtime Log** | `pipeline.log` *(optional)* | Execution time and process messages |

---

### 📁 Example Output Directory Structure

