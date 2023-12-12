# MethylationChip_Practice
Practice for epigenome wide association sutdy including QC, DMP, DMR and meQTL. 
* **Data** <br />
  Blood samples from 60 individuals (34 controls, 26 cases) <br />
  1. Methylation data : EPIC BeadChip 850K - idat files in `idats` folder
  2. Genotype data : KoreanChip - txt file in `SNPdata` (preprocessed)
  3. Phenotype data : Disease, Age, Sex (randomly assigned)

* **Tutorial workflow** <br />
  1. QC of
  2. DMP and DMR analysis
  3. meQTL analysis 

* **Required R packages**
  |Package Name|R code installation |
  |------------|-------------------|
  |ewastools   |remotes::install_github("hhhh5/ewastools")|
  |illuminaio  |BiocManager::install("illuminaio")|
  |lumi        |BiocManager::install("lumi")|
  |svd         |install.packages("svd")|
  |data.table  |install.packages("data.table")|
  |dplyr       |install.packages("data.table")|
  |limma       |BiocManager::install("limma")|
  |DMRcate     |BiocManager::install("DMRcate")|
  |MatrixEQTL  |install.packages("MatrixEQTL")|
