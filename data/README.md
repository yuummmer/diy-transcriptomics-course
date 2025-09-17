# data/

This folder holds input files for the transcriptomics workflow.

## Contents
- `studydesign.txt` – sample metadata (tracked in Git).
- `kallisto/` – directory containing kallisto quantification outputs for each sample.
  - Expected layout: `data/kallisto/<SAMPLE_ID>/abundance.tsv`

## Notes
- Raw FASTQ files and kallisto outputs are **not tracked in Git** because of their size.  
- To reproduce the analysis, download the raw RNA-seq data from GEO accession: **[INSERT ACCESSION HERE]**, run kallisto quantification, and place the outputs under `data/kallisto/`.

## Optional
- `archs4/` – (not tracked) place downloaded ARCHS4 `.h5` files here if you want to run the optional ARCHS4 analysis steps. See scripts for details.
