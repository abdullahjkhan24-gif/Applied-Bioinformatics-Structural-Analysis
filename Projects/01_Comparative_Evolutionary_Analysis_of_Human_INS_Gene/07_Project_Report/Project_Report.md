# Comparative Evolutionary Analysis of the Human Insulin (INS) Gene

**Student:** Abdullah Jawad  
**Project:** Comparative Evolutionary Analysis of the Human Insulin (INS) Gene

## Objective
The aim was to investigate conservation of the insulin gene across vertebrates by retrieving the human INS reference sequence, compiling homologous insulin sequences, aligning them and constructing a Neighbor-Joining phylogenetic tree.

## Reference sequence
The human reference used was NCBI RefSeq **NM_000207.3**, encoding insulin preproprotein **NP_000198.1**. NCBI describes INS as encoding a peptide hormone with a central role in carbohydrate and lipid metabolism.

## Analysis
A curated homolog panel was assembled from documented INS accessions. Nine real insulin sequences were used for the computed alignment: human, rat insulin 2, sheep, cat, mouse insulin 1, rabbit, pig, zebrafish and Xenopus. A progressive global alignment against the human reference was used to produce the repository alignment, followed by an identity-distance matrix and Neighbor-Joining tree.

## Results and interpretation
The alignment shows strong conservation across the insulin family, especially around the mature insulin B- and A-chain regions. The human sequence clusters most closely with other mammalian insulin sequences, while the mouse and rat sequences form a particularly close pair in the computed tree. Rabbit also lies near the human/rodent portion of the mammalian cluster. Sheep and pig form a separate mammalian branch in this small representative dataset, reflecting greater sequence differences in precursor/C-peptide regions. Cat is also placed within the mammalian group but is more distant than the closest rodent pair. Zebrafish and Xenopus are substantially more distant in the tree, consistent with their deeper evolutionary separation from mammals.

The pattern supports the biological expectation that insulin is an evolutionarily conserved peptide hormone. The mature insulin chains are more constrained than the precursor regions, because the functional hormone must preserve residues needed for receptor binding and disulfide-bonded structure. Differences in the signal peptide and C-peptide/connecting regions contribute more strongly to sequence distance.

## Limitation and reproducibility
The repository does **not** invent BLASTx E-values, bit scores, query coverage or screenshots. The homolog table therefore records accession-level candidates rather than pretending to be a numerical BLAST report. The MSA and Neighbor-Joining calculations included in this repository are actual computations from the deposited sequences. The final iTOL file is prepared as an upload-ready Newick tree; no iTOL export screenshot is claimed until the tree is uploaded and exported through iTOL.

## Conclusion
Human INS is strongly conserved among vertebrates, with mammalian sequences grouping together and fish/amphibian sequences showing greater divergence. Conservation of the mature insulin regions supports their functional importance, while greater variation in precursor regions provides evolutionary signal for distinguishing lineages.

## References

1. NCBI RefSeq: Homo sapiens insulin (INS), transcript variant 1, NM_000207.3.
2. UniProtKB P01308: INS_HUMAN.
3. UniProtKB P01311: INS_RABIT.
4. UniRef/UniProt insulin family records.
5. BioCode Innovators internship project instructions and demonstration repository structure.
