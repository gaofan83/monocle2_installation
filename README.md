### Monocle2 installation on Windows
#### Install R3.6.0
#### Install Rstudio
#### Install Rtools35
##### `wget https://cran.r-project.org/src/contrib/Archive/VGAM/VGAM_1.1-1.tar.gz`
##### `wget https://cran.r-project.org/src/contrib/Archive/irlba/irlba_2.3.3.tar.gz`
##### `wget https://cran.r-project.org/src/contrib/Archive/tidyselect/tidyselect_1.1.0.tar.gz`
##### `wget https://cran.r-project.org/src/contrib/Archive/fastICA/fastICA_1.2-2.tar.gz`
```{r}
install.packages("C:/Users/caltech/Downloads/VGAM_1.1-1.tar.gz", repos = NULL, type = "source")
install.packages("C:/Users/caltech/Downloads/irlba_2.3.3.tar.gz", repos = NULL, type = "source")
install.packages("C:/Users/caltech/Downloads/tidyselect_1.1.0.tar.gz", repos = NULL, type = "source")
install.packages("C:/Users/caltech/Downloads/fastICA_1.2-2.tar.gz", repos = NULL, type = "source")
```

```{r}
install.packages("shiny")
install.packages("htmlwidgets")
install.packages("devtools", type="source")
if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
install.packages("pillar", type="source")
BiocManager::install("monocle", type="source")
BiocManager::install("monocle") 
#Download Seurat 3.2.0
install.packages(c("ape", "cowplot", "fitdistrplus", "future", "future.apply", "ggridges", "ica", "leiden", "lmtest", "patchwork", "pbapply", "plotly", "png", "RcppAnnoy", "reticulate", "ROCR", "rsvd", "sctransform", "spatstat", "uwot", "RcppProgress"))
install.packages("reticulate") #use binary 
install.packages("igraph", type="binary")
install.packages("leiden", type="binary")
install.packages("rsvd", type="binary")
install.packages("sctransform", type="binary")
install.packages('https://cran.r-project.org/src/contrib/Archive/spatstat/spatstat_1.64-1.tar.gz', repos=NULL,type="source")
install.packages("C:/Users/caltech/Downloads/seurat-3.2.0.tar.gz", repos = NULL, type = "source")

```
