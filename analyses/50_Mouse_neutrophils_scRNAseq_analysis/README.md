# Sc-RNAseq analysis of mouse neutrophils and progenitors from healthy and tumor-bearing mice

## Data availability 
Data can be downloaded from GEO under accession number: GSE285117. 

## Scripts: 
**1.Packages_and_functions.R**: Packages and function that need to be loaded for the following analysis

**2.Data_preprocessing.R**: Integration of cell-count matrices into the Seurat workflow and initial quality cutoff to remove cells with < 200 and > 5000 genes and > 25 % mitochondrial reads

**3.1.Annotation_and_extraction_of_neutrophils.R**: Annotation to extraction neutrophils from all datasets

**3.2.Annotation_and_extraction_progentors.R**: Annotation to extract progenitors from bone marrow derived datasets

**4.Neutrophil_integration.R**: Integration of neutrophils from colon, tumor, NAT, disseminated, blood and bone marrow from healthy and tumor-bearing mice

**4.2.Neutrophils_Progenitor_integration.R**: Integration of neutrophils and progenitors from colon, tumor, NAT, disseminated, blood and bone marrow from healthy and tumor-bearing mice

**5.Neutrophils_cross_species_comparison.R**: Analysis of ortholog genes that were found to be specific for human tumor-associated and blood neutrophil (TAN and BN) clusters in mouse neutrophil clusters

**6.Neutrophils_slingshot_trajectory_analysis.R**: Pseudotime trajectory analysis using Slingshot and tradeSeq

**6.2.Neutrophils_slingshot_analysis_between_phenotypes.R**: Pseudotime trajectory analysis using Slingshot and tradeSeq comparing healthy and tumor derived tissues

**7.Neutrophils_DEG_analysis.R**: DEG analysis of blood and bone marrow derived neutrophils comparing healthy and tumor 

**7.1.Neutrophils_prog_DEG_analysis.R**: DEG analysis of progenitors comparing healthy and tumor 

**8.Neutrophils_cluster10.R**: Analysis of cluster 10 based on gene expression and cell cycle score.  

