
<!-- README.md is generated from README.Rmd. Please edit that file -->

# SeuratObject

<!-- badges: start -->

[![Lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://github.com/mojaveazure/seurat-object)
[![CRAN/METACRAN](https://img.shields.io/cran/v/SeuratObject)](https://cran.r-project.org/package=SeuratObject)
[![dependencies](https://tinyverse.netlify.com/badge/SeuratObject)](https://cran.r-project.org/package=SeuratObject)
[![Downloads](https://cranlogs.r-pkg.org/badges/SeuratObject?color=brightgreen)](https://cran.r-project.org/package=SeuratObject)
<!-- badges: end -->

Defines S4 classes for single-cell genomic data and associated
information, such as dimensionality reduction embeddings,
nearest-neighbor graphs, and spatially-resolved coordinates. Provides
data access methods and R-native hooks to ensure the Seurat object is
familiar to other R users.

## Installation

SeuratObject is not currently available on CRAN. You can install it from
[GitHub](https://github.com/mojaveazure/seurat-object) with:

``` r
if (!requireNamespace("remotes", quietly = TRUE)) {
  install.packages("remotes")
}
remotes::install_github("mojaveazure/seurat-object")
```
