# BLAST Annotation Pipeline

## Project Overview

This project performs protein annotation using BLASTP. Five E. coli protein sequences (ORFs) were selected and searched against the NCBI non-redundant (nr) protein database using Biopython's `NCBIWWW.qblast()`.

The BLAST XML results were parsed to extract the top hits. The hits were filtered using an E-value threshold of less than 1e-10 and an identity greater than 40%. A final annotation table was generated, and a pie chart was created to summarize the functional categories of the identified proteins.

## Objectives

- Extract protein sequences from E. coli.
- Run BLASTP searches using NCBI.
- Parse BLAST XML output.
- Filter high-confidence matches.
- Generate a final annotation table.
- Visualize functional categories with a pie chart.

## Tools Used

- Python
- Biopython
- Pandas
- Matplotlib
- Jupyter Notebook

## Input

- E. coli protein FASTA file
- BLAST XML files

## Output

- final_annotation_table.csv
- functional_categories_pie.png

## Filtering Criteria

- E-value < 1e-10
- Identity > 40%

## Author

Popoola Aabdulgafar
Bioinformatics
