# T1D-Immune-Environment-Study
The code is used to analyze scRNAseq data of T1D immune cells.

**Data filter.Rmd:** To filter out the barcodes with low quality, making sure that the barcodes for downstream analysis are reliable. 


**Annotation by label transfer.Rmd:** Showing the process of ReBeLa: transfer the cell type annotation from the annotated public dataset to our own data, generate clusters with high resolution, and remove the clusters with a mixture of annotated cell types. This code was used to define major immune cell types, T cell subtypes, and macrophage subsets.


**PD1 cell define.Rmd:** Showing the process of defining the PD-1+ cell based on the Pdcd1-corralted 17-gene. 


**DEG and pathways.Rmd:** Showing the process of filtering DEGs and the pathway analysis based on those DEGs.
