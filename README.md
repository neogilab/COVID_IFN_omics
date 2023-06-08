# Systemic multiomics analysis defines the heterogenous interferon response landscape in COVID-19 severity 

## Description
Multi-omics characterization of COVID-19 patients based on interferon profile

## Installation

### Clone the repository
```
git clone https://github.com/neogilab/COVID_IFN_omics.git
cd COVID_IFN_omics
```

### Requirements

1. A linux distribution

2. R and R studio environment and following packages
Open R and run
```
# install and load  the package  manager
 if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
    
 bio_pkgs <- c("ComplexHeatmap", "ggpubr", "ggplot2", "ggvenn", 
          "Hmisc", "GSVA", "limma", "DESeq2", "ConsensusClusterplus")

# install:
BiocManager::install(bio_pkgs)
```

### Run code

1) Create folders
```
Rscript create_folders.R
```

2) Move data files to folder data
3) Change path to your own computer
4) Execute R notebooks for producing tables and figures

### Author

Flora Mikaeloff
