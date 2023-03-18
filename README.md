# INTRODUCTION
Single-cell RNA sequencing (scRNA-seq) is a powerful technique that allows researchers to profile the transcriptome of individual cells, enabling us to infer from marker genes the putative cell types in the data.
The data used was collected for the 2019 study ‘Adventitial Stromal Cells Define Group 2 Innate Lymphoid Cell Tissue Niches’ by Dahlgren, M.W. et al.  (DOI: 10.1016/j.immuni.2019.02.002).

Aim of the study was understanding the phsysical niche of type 2 lymphocytes.


## QUALITY CONTROL
We removed cells with:
- a read count lower than 200 
- a read count higher 2000 
- a percentage of mitochondrion RNA higher 5%


## ANALYSIS 
Principal Component Analysis (PCA) was performed the dataset. 
The 3 most variable genes along the first component are coding for Surfactant, Pulmonary-Associated Protein, associated with epithelial cells of lung.

Two different clustering attempts are shown:
One with 12 Principal components (PCs) - graphically chosen from the elbow plot and one with 22  as it was the number of components able to explain 75% of the variance. 
The comparison between the two clustering showed no interesting subs clusters in the 22 PCs variant compared to the 12 PCs one and the 12 PCs clustering was kept to find marker genes. 


## RESULTS
Following cells were found 
- Epithelial cells
- Mesenchimal cells
- Endothelial alveolar cells 
- Mesothelial cells 
- Endothelial cells 
- Myocardial cells (probably a sample contamination)

Analysis performd with @sabrisart
