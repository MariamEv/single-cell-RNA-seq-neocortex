# single-cell-RNA-seq-neocortex
Neocortex is a region in the brain which governs higher-level functions such as perception and cognition. 


single-cell RNA-seq dataset, with the goal of unveiling hierarchical structure and discovering important genes. The datasets provided are all different subsets of a larger single-cell RNA-seq dataset, compiled by the Allen Institute. This data contains cells from the mouse neocortex, a region in the brain which governs higher-level functions such as perception and cognition.

**About Dataset:
**
The single-cell RNA-seq data comes in the form of a counts matrix, where

- each row corresponds to a cell

- each column corresponds to the normalized transcript compatibility count (TCC) of an equivalence class of short RNA sequences, rescaled to units of counts per million. You can think of the TCC entry at location: (i,j) of the data matrix as the level of expression of the i-th gene in the j-th cell: (Gene, Cell)
