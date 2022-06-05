# Project 2 : HIV protein envelope & CD4-protein

## Scientific Question:

Does the HIV protein envelope binds to primary cellular receptor CD4 protein of any organism other than human and causes infection? 

## Hypothesis:

If we found high similarity between human CD4 glycoprotein and other organism's CD4 protein then, HIV virus can binds to those proteins and potentially initiates infection similar to human? 

## Bioinformatics Method and Visualization used

In this bioinformatics analysis I performed various alignment methods including pairwise alignment using Biostrings library function, multiple sequence alignment using msa library function and BLAST analysis using bio3d library functions. The alignment describes how the sequences and structures are similar to each other. 

Further I used residue identification, 3D structural analysis and visualization of all the 5 structures of selected proteins. 3 out of 5 proteins didn't have their structure calculated but they were available via Alphafold predicted structure. I used them as well in the analysis and compared. 

## File description

#### Ali_Project2D.Rmd 
This is the main R notebook containing all code for this analysis. Running this file will produce a HTML file similar to "Ali_Project2D.html". 

#### CD4_5Org_uniprot.fasta
This a FASTA format file containing CD4 protein sequences from 5 different organism (Human, RAT, PANTR, MOUSE, and CANLF) . This will be required for running above R notebook.

### Protein Structures (Uniprot | ID Organism | Protein ID )

1. P01730 | Human 1CDH
2. P05540 | RAT | 1CID
3. P16004 | PANTR | AF-P16004-F1-model_v2
4. P06332 | MOUSE | AF-P06332-F1-model_v2
5. P33705 | CANLF | AF-P33705-F1-model_v2

_For protein seequences with IDs P16004, P06332, and P33705 there were no PDB structure available from RSCB or any other source. Rather only predicted structures were present from AlphaFold._
