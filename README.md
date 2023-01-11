# R packages for my daily scientific work <!-- omit in toc -->


My personal curated list of useful R packages and extensions for my work as a life science scientist.  


<hr>

- Inspired by: [awesome-react-components](https://github.com/nanxstats/awesome-shiny-extensions) and [awesome-rshiny](https://github.com/grabear/awesome-rshiny).

<hr>

- [workhorse](#workhorses)
- [statistics](#statistics)
  - [general](#general)
  - [genetics](#genetics)  
- [ggplot2](#ggplot)
- [shiny](#shiny)

## workhorse

*Packages I load in the beginning of every session*

- [tidyverse](https://www.tidyverse.org/) - bundel of useful packages
- [janitor](https://cran.r-project.org/web/packages/janitor/index.html) - tool for cleaning and examin "dirty" data 
- [readxl](https://readxl.tidyverse.org/) - get easily and fastly data out of Excel into `R`
- [glue](https://glue.tidyverse.org/) - enhanced string manipulation
- [furrr](https://furrr.futureverse.org/) - `purrr`'s mapping functions but in parallel mode


## statistics

*Science without pvalues is barly not possible*

### general

- [rstatix](https://github.com/kassambara/rstatix) - (tidyverse) pipe-friendly framework for basic statistical tests
- [gtsummary](https://www.danieldsjoberg.com/gtsummary/) - elegant and flexible way to create publication-ready analytical and summary tables
- [pROC](https://cran.r-project.org/web/packages/pROC/pROC.pdf) - Tools for visualizing, smoothing and comparing ROC curves
- [quantreg](https://cran.r-project.org/web/packages/quantreg/index.html) - quantile regression for non-parametric data

### genetics

- [haplo.stats](https://cran.r-project.org/web/packages/haplo.stats/index.html) - analysis of haplotypes.
- [SNPassoc](https://cran.r-project.org/web/packages/SNPassoc/index.html) - Useful for small genetic association studies
- [SKAT](https://cran.r-project.org/web/packages/SKAT/index.html) - gene-based association tests and other burden tests
- [ggfastman](https://github.com/roman-tremmel/ggfastman) - plotting tons of pvalues using manhatten plots


## ggplot2

- [ggpubr](https://rpkgs.datanovia.com/ggpubr) - easy-to-use functions for creating ‘ggplot2’- based publication ready plots including statistical add ons.
- [ggsignif](https://cran.r-project.org/web/packages/ggsignif/vignettes/intro.html) - visualization of statistical differences
- [ggbeeswarm](https://github.com/eclarke/ggbeeswarm) - Beeswarm plots aka scatter plots or violin/boxplot plots with points
- [cowplot](https://cran.r-project.org/web/packages/cowplot/vignettes/introduction.html#:~:text=The%20cowplot%20package%20is%20a,or%20mix%20plots%20with%20images.) -creating publication-quality figures
- [ggrepel](https://cran.r-project.org/web/packages/ggrepel/vignettes/ggrepel.html) - annotations without overlapp
- [ggannotate](https://github.com/MattCowgill/ggannotate) - point-and-click tool to annotate plots in the last production step


