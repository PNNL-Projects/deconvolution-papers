# deconvolution-papers

A number of algorithms have recently been developed for deconvolution of cell types in bulk RNA-seq samples based on cell type signatures derived from single-cell RNA-seq data. This repository contains a list of recent algorithms and application papers, along with our comments on them.

The list is organized into two parts: (i) method papers describing algorithms, and (ii) application papers. The list will be added to over time.



## Method papers

Method | Reference | Availability | Comments
:----- | :-------- | :----------- | :-------
CIBERSORT | [Newman et al. (2015), Nature Methods](https://www.nature.com/articles/nmeth.3337) | [Online tool](https://cibersort.stanford.edu/) requiring signup and login. | Requires input matrix of reference gene expression signatures for cell types. Methodology is based on linear support vector regression, which also performs feature selection on the genes in the signature matrix. Also returns overall p-value for null hypothesis that no cell types from the signature matrix are present. Extensive benchmarking on datasets with both simulated and experimental (e.g. flow sorted) ground truth, and comparison against several earlier methods (using microarray data only). Currently appears to be the most widely used tool.
CIBERSORTx | [Newman et al. (2019), Nature Biotechnology](https://www.nature.com/articles/s41587-019-0114-2) | [Online tool](https://cibersortx.stanford.edu/) requiring signup and login. Freely available for academic use only. | 
DWLS | [Tsoucas et al. (2019), Nature Communications](https://www.nature.com/articles/s41467-019-10802-z) | [R package from BitBucket](https://bitbucket.org/yuanlab/dwls/src/default/) | 
Bisque | [Jew et al. (2019), bioRxiv](https://www.biorxiv.org/content/10.1101/669911v1) | [R package from GitHub](https://github.com/cozygene/bisque) | 
Scaden | [Menden et al. (2019), bioRxiv](https://www.biorxiv.org/content/10.1101/659227v1) | [Python 3 package from Bioconda and PyPI](https://github.com/KevinMenden/scaden) | 



## Application papers

Application papers listed here will be mainly from the field of ovarian cancer.

