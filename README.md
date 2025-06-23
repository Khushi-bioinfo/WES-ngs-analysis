# WES-ngs-analysis
Pipeline for variant calling and annotation using whole exome sequencing (WES) data


WS Variant Analysis - Escherichia coli K12
This project performs whole-exome  sequencing (WGS) variant calling and annotation on SRR000964

## 📌 Dataset
- **Accession ID:** [SRR000964](https://trace.ncbi.nlm.nih.gov/Traces/sra/?run=SRR000964)  
- **Organism:** *Homo sapiens*  
- **Sequencing Type:** Whole Exome Sequencing (WES)

## Folder Structure

- `data/` – Raw FASTQ and reference genome files.
- `scripts/` – Bash scripts for each processing step.
- `results/` – Filtered/annotated VCFs, BAM files, and FastQC reports.
- `docs/` – SNP annotation summary HTML and supporting documentation.

## Tools Used
- FastQC
- BWA
- SAMtools
- BCFtools
- SnpEff

## Pipeline Overview

1. Quality check with FastQC
2. Alignment using BWA
3. BAM conversion and sorting with SAMtools
4. Variant calling with BCFtools
5. Variant filtering
6. Annotation with SnpEff


Folder Structure
'data/ – Raw FASTQ and reference genome files.
scripts/ – Bash scripts for each processing step.
results/ – Filtered/annotated VCFs, BAM files, and FastQC reports.
docs/ – SNP annotation summary HTML and supporting documentation.
Tools Used
FastQC
BWA
SAMtools
BCFtools
SnpEff
Pipeline Overview
Quality check with FastQC
Alignment using BWA
BAM conversion and sorting with SAMtools
Variant calling with BCFtools
Variant filtering
Annotation with SnpEff
