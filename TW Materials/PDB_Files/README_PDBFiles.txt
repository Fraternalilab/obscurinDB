PDB structures and session files for annotated models

## PDB model summary

Table of existing PDB models as of Jan 2019
- mapped to corresponding UniProt (Q5VST9) obscurin-b domain
- noted how much of model is included in Q5VST9 domain
- also sequence ID to particular models (based on BLAST, ID based only on partial match in most cases - see the column for specific numbers)

## [Domain_Name]_[PDB_Accession]

PDB models created by homology modelling (SWISS-MODEL)
- PDB files give the domain name and the PDB accession file that was used for homology modelling that domain (NOT necessarily the same domain as the sequence)
- eg. Ig1_4C4K is OBSCN-IC immunoglobulin domain 1, modelled on PDB model 4C4K (which is also OBSCN-IC Ig1 with additional bases)
- eg. Ig68_3LCY is OBSCN-IC immunoglobulin domain 68, modelled on PDB model 3LCY (which is titin Ig domains A164-A165)

## Session Files

PDB Session files of annotated models
- Rare Muts: Pathogenic Ig domain SNVs mapped to respective structural positions on Ig59 (5TZM) after alignment of Ig domains by T-Coffee
- Common Muts: Ig domain SNVs with frequency >100,000 in gnomAD database mapped to respective structural positions on Ig59 (5TZM) after alignment of Ig domains by T-Coffee
- Stability_Ig1 - Common SNVs from Ensembl mapped to Ig1 (Ig1_4C4K) and annotated according to associated protein stability change computed by mCSM (green=stabilising -> yellow=destabilising -> red=highly destabilising)
- Stability_Ig1_M10 - Common SNVs from Ensembl mapped to Ig1 / titin M10 complex (4C4K) and annotated according to associated protein affinity change computed by mCSM (green=stabilising -> yellow=destabilising -> red=highly destabilising)