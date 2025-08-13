This repository contains a curated COI (cytochrome c oxidase subunit I) reference database for UK amphibian species, intended for use in metabarcoding and biodiversity monitoring studies.

Contents
COI_final_filtered.fasta – FASTA file containing reference sequences.

Usage
You can use this database for:

BLAST searches to identify COI sequences from UK amphibians.

Metabarcoding workflows involving VSEARCH, QIIME2, or similar tools.
Example usage (Bash code)
vsearch --usearch_global query_sequences.fasta \
  --db COI_final_filtered.fasta \
  --id 0.9 \
  --blast6out results.txt
