# MethylationChip_Practice
Practice for epigenome wide association sutdy including QC, DMP, DMR and meQTL. 
* **Data** <br />
  Blood samples from 60 individuals (30 controls, 30 cases) <br />
  1. Methylation data : EPIC BeadChip 850K - idat files in `idats` folder
  2. Genotype data : KoreanChip - txt file in `SNPdata` (preprocessed)
  3. Phenotype data : Disease, Age, Sex (randomly assigned)

* **Tutorial workflow** <br />
  1. QC of
  2. DMP and DMR analysis
  3. meQTL analysis 

* **Required R packages**
  |Package Name|Installation R code|
  |------------|-------------------|
  |ewastools   |remotes::install_github("hhhh5/ewastools")|
  |illuminaio  |BiocManager::install("illuminaio")|
  |svd         |install.packages("svd")|
  |data.table  |install.packages("data.table")|
  |dplyr       |install.packages("data.table")|
  |limma       |BiocManager::install("limma")|
  |DMRcate     |BiocManager::install("DMRcate")|
  |MatrixEQTL  |install.packages("MatrixEQTL")|
