# Project 1 — Comparative Evolutionary Analysis of the Human INS Gene

**Student:** Abdullah Jawad

## Objective
Investigate evolutionary conservation of human insulin (INS) by comparing homologous insulin precursor proteins from vertebrates, aligning the sequences, constructing a Neighbor-Joining tree, and interpreting the resulting conservation pattern.

## Internship workflow
NCBI sequence retrieval → BLASTx homolog search → selected homologs → ClustalW multiple sequence alignment in MEGA 12 → Neighbor-Joining phylogenetic tree → iTOL visualization → 200–300 word interpretation.

## Required seven-folder structure
1. `01_Project_Guidelines`
2. `02_NCBI_Sequence`
3. `03_BLASTx_Analysis`
4. `04_Multiple_Sequence_Alignment`
5. `05_Phylogenetic_Tree`
6. `06_iTOL_Visualization`
7. `07_Project_Report`

This folder structure matches the structure explicitly shared by the instructor in the internship chat and is also present in Sada Fuad's Projects repository. The instructor's demo says the first folder should contain a brief project description, workflow, interpretation guidance and questionnaire/checklist.

## Important methodological note
The human reference is the current NCBI RefSeq transcript **NM_000207.3**, encoding **NP_000198.1**. The actual comparative analysis in this repository uses real INS protein sequences/accessions and computes the alignment and tree from those sequences. NCBI/BLAST numerical scores are not fabricated; any field marked as a candidate/homolog panel is not presented as a BLAST score.
