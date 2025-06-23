## Whole Exome Sequencing Analysis Scripts
This directory contains all the bash scripts used to run the Whole Exome Sequencing (WES) variant calling and annotation pipeline.
Specifically, they cover:
- Uploading the reference FASTA genome
- Quality control (QC) of raw reads
- Trimming low-quality bases and adapters using Fastp
- Indexing the reference genome
- Mapping reads to the reference using BWA
- Variant calling and filtering
- Functional variant annotation using SnpEff
