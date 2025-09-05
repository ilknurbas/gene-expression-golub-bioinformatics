### Gene Expression Analysis in Leukemia Patients using Golub Dataset

This project analyzes the Golub leukemia dataset using multivariate statistical methods to explore gene expression patterns:

**`Key Steps & Techniques:`**

+ **Dataset:** Golub gene expression data (3051 genes × leukemia samples)

+ **Data Processing:** Extracted specific gene expression vectors and computed average expressions

+ **Visualization:** Boxplots, heatmaps, and dendrograms for expression comparison and clustering

+ **Dimensionality Reduction:** PCA on gene subsets and the full dataset

+ **Clustering:** k-means and hierarchical clustering to identify gene expression patterns

+ **Tools:** R, Bioconductor (multtest), base R plotting

**`Highlights:`**

+ Identified top correlated and anti-correlated genes with target gene (9th row)

+ Visualized gene expression clusters and principal components

+ Explored dimensionality reduction impact on clustering patterns

**`Usage:`**

```
# Install dependencies
BiocManager::install("multtest")

# Run analysis
source("golub_analysis.R")
```
