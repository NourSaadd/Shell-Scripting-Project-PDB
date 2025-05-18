# PDB Structure Analysis – Shell Scripting Project

This project presents a complete Linux shell scripting workflow for retrieving, filtering, and analyzing PDB (Protein Data Bank) files. 
It was completed as part of the Script Programming course.

The goal was to use scripting techniques to automate the handling of structured biological data and extract useful insights such as amino acid frequencies from structural files.

## Overview

Protein structure data is often stored in PDB format and accessed through public databases like the RCSB PDB. This project simulates a real-world scenario where researchers need to process dozens of structures to identify patterns and clean datasets. 
The pipeline performs:

- Batch downloading of PDB files from the RCSB database
- Removal of files that are invalid or unavailable
- Extraction of amino acid types based on alpha carbon (CA) atoms
- Filtering of multi-model files to prevent overcounting residues

The project emphasizes accuracy, reproducibility, and practical scripting in a bioinformatics context.

## Tools Used

- Bash Shell (Linux terminal)
- curl
- grep
- awk
- cut
- sort
- uniq
- xargs

## Team

This project was completed by:

- Nour Saad  
- Joudy Allam
