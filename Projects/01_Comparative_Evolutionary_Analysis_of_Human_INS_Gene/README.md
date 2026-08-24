# Comparative Evolutionary Analysis of the Human Insulin (INS) Gene

**Student:** Abdullah Jawad  
**Internship:** Bioinformatics & Molecular Docking Internship — BioCode Innovators  
**Project:** 01 — Sequence Analysis / Evolutionary Biology

## Objective
Investigate the evolutionary relationships of the human insulin (**INS**) gene by comparing homologous sequences from diverse vertebrate species, performing multiple sequence alignment, and constructing a phylogenetic tree.

## Workflow

NCBI → Reference INS sequence → BLAST/BLASTx homolog search → selected vertebrate homologs → ClustalW MSA in MEGA → Neighbor-Joining phylogenetic tree → iTOL visualization → biological interpretation

## Folder structure

- `01_Project_Guidelines/` — project objective, workflow, criteria and checklist
- `02_NCBI_Sequence/` — reference sequence metadata and downloaded FASTA files
- `03_BLASTx_Analysis/` — BLAST search method, selected homolog table and result notes
- `04_Multiple_Sequence_Alignment/` — MSA inputs, MEGA notes and alignment outputs
- `05_Phylogenetic_Tree/` — Neighbor-Joining tree notes and output metadata
- `06_iTOL_Visualization/` — final tree visualization notes and annotation files
- `07_Project_Report/` — final scientific report and references

## Reference sequence

The curated human INS transcript is **NM_000207.3**, encoding **NP_000198.1** (insulin preproprotein). NCBI lists the human INS gene as Gene ID 3630 and describes insulin as a peptide hormone involved in carbohydrate and lipid metabolism.

## Reproducibility note

This project documents the workflow and accession information without fabricating BLAST scores, alignment statistics, tree topology, or screenshots. Numerical results should be copied from the actual NCBI/BLAST, MEGA and iTOL runs and placed in the corresponding folders.

## Status

- [x] Project structure created
- [x] Objective and workflow documented
- [x] Reference accession identified
- [ ] Attach NCBI FASTA export
- [ ] Attach BLAST output/screenshot
- [ ] Attach selected homolog FASTA
- [ ] Attach MEGA alignment
- [ ] Attach Neighbor-Joining tree
- [ ] Attach iTOL visualization
- [ ] Finalize results/discussion
