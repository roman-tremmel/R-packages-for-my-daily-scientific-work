# R packages for my daily scientific work <!-- omit in toc -->


My personal curated list of useful R packages and extensions for my work as researcher in life science with focus on (pharmaco)genetics, clinical studies, OMICS and shiny apps.  


<hr>

- Inspired by: [awesome-react-components](https://github.com/nanxstats/awesome-shiny-extensions) and [awesome-rshiny](https://github.com/grabear/awesome-rshiny).

<hr>

# Overview

- [workhorse](#workhorses)
- [statistics](#statistics)
  - [general](#general)
  - [genomics](#genomics)
  - [machine learning](#machine-learning)
- [ggplot2](#ggplot)
- [shiny](#shiny)
- [others](#others)
  - [R packages](#R-packages)
  - [cmdline tools](#cmdline-tools)

## workhorse

*Packages I load in the beginning of almost every session*

- [tidyverse](https://www.tidyverse.org/) - bundel of useful packages
- [janitor](https://cran.r-project.org/web/packages/janitor/index.html) - tool for cleaning and examin "dirty" data 
- [readxl](https://readxl.tidyverse.org/) - get easily and fastly data out of Excel into `R`
- [glue](https://glue.tidyverse.org/) - enhanced string manipulation
- [furrr](https://furrr.futureverse.org/) - `purrr`'s mapping functions but in parallel mode
- [fst](https://www.fstpackage.org) - saving and loading data extremely fast


## statistics

*Science without pvalues is barly not possible*

### general

- [rstatix](https://github.com/kassambara/rstatix) - (tidyverse) pipe-friendly framework for basic statistical tests
- [gtsummary](https://www.danieldsjoberg.com/gtsummary/) - elegant and flexible way to create publication-ready analytical and summary tables
- [pROC](https://cran.r-project.org/web/packages/pROC/pROC.pdf) - tools for visualizing, smoothing and comparing ROC curves
- [quantreg](https://cran.r-project.org/web/packages/quantreg/index.html) - quantile regression for non-parametric data
- [coin](https://cran.r-project.org/web/packages/coin/index.html) - functions to transform data and a lot of tests
- [breakerofchains](https://github.com/MilesMcBain/breakerofchains) - Run your chain until the cursor line. Add the addin by using a shortcut like 'Ctrl + shift + b'. 

### genomics

- [haplo.stats](https://cran.r-project.org/web/packages/haplo.stats/index.html) - analysis of haplotypes.
- [SNPassoc](https://cran.r-project.org/web/packages/SNPassoc/index.html) - useful for small genetic association studies
- [SKAT](https://cran.r-project.org/web/packages/SKAT/index.html) - gene-based association tests and other burden tests
- [ggfastman](https://github.com/roman-tremmel/ggfastman) - plotting tons of pvalues using manhatten plots
- [pathfindR](https://github.com/egeulgen/pathfindR) - pathway enrichment analysis via active subnetworks

### machine learning

- [caret](https://topepo.github.io/caret/) - toolset for classification and regression models
- [caretEnsemble](https://cran.r-project.org/web/packages/caretEnsemble/vignettes/caretEnsemble-intro.html) - ensembles of caret models allows also to use bootstrapping
- [superlearner](https://cran.r-project.org/web/packages/SuperLearner/vignettes/Guide-to-SuperLearner.html) - easily estimate the performance of multiple machine learning models using cross validation



## ggplot2

*ggplot extension for further and easy customisation*

- [ggpubr](https://rpkgs.datanovia.com/ggpubr) - easy-to-use functions for creating ‘ggplot2’- based publication ready plots including statistical add ons.
- [ggsignif](https://cran.r-project.org/web/packages/ggsignif/vignettes/intro.html) - visualization of statistical differences
- [ggbeeswarm](https://github.com/eclarke/ggbeeswarm) - beeswarm plots aka scatter plots or violin/boxplot plots with points
- [cowplot](https://cran.r-project.org/web/packages/cowplot/vignettes/introduction.html#:~:text=The%20cowplot%20package%20is%20a,or%20mix%20plots%20with%20images.) -creating publication-quality figures
- [ggrepel](https://cran.r-project.org/web/packages/ggrepel/vignettes/ggrepel.html) - annotations without overlapp
- [ggannotate](https://github.com/MattCowgill/ggannotate) - point-and-click tool to annotate plots in the last production step
- [plotly](https://plotly.com/r/) - interactive plots
- [ggtex](https://wilkelab.org/ggtext/) -  Add nice text, lables and boxes to your ggplots 


## shiny

*there are better lists as linked above, but I use following packages very often*

- [shinydashboard](https://rstudio.github.io/shinydashboard/) - easy way to create dashboards
- [shinydashboardPlus](https://rinterface.github.io/shinydashboardPlus/) - nice features beyond the original dashboard
- [shinyWidgets](https://github.com/dreamRs/shinyWidgets) - additional and nicer inputs
- [shinyjs](https://deanattali.com/shinyjs/) - useful to integrate JavaScript in shiny code 
- [bslib](https://rstudio.github.io/bslib/) - customizing bootstrap themes for shiny  

## others

*packages not fitting 100% in the categories above and other commandline tools*

### R packages
- [clinPK](https://github.com/InsightRX/clinPK) - functions for clinical pharmacokinetics and clinical pharmacology
- [valr](https://rnabioco.github.io/valr/) - compare and manipulate genome intervals
- [gplots](https://cran.r-project.org/web/packages/gplots/index.html) - useful for heatmaps and venn diagrams
- [disgenet2r](https://www.disgenet.org/static/disgenet2r/disgenet2r.html#contact) - information about the genetic basis of human diseases


### cmdline tools
- [plink](https://zzz.bwh.harvard.edu/plink/) - whole genome association analysis toolset
- [snptest](https://www.well.ox.ac.uk/~gav/snptest/) - genome-wide association analysis of SNPs
- [regenie](https://rgcgithub.github.io/regenie/) - whole genome regression modelling of massive large GWAS
- [vep](https://www.ensembl.org/info/docs/tools/vep/index.html) - genetic variant annotation including effects and functions
- [SNpeff](http://pcingola.github.io/SnpEff/) - genomic variant annotations and functional effect prediction toolbox
- [pypgx](https://github.com/sbslee/pypgx) - pharmacogenomics profiles from NGS & SNP array data
- [aldy](https://github.com/0xTCG/aldy) - pharmacogenomics profiles from NGS data
- [samtools](http://www.htslib.org/) - toolbox for high-throughput sequencing data
- [openai](https://openai.com/) - API to access GPT-3
- [celltypist](https://www.celltypist.org/) - automated cell type annotation for scRNA-seq
- [salmon](https://salmon.readthedocs.io/en/latest/index.html) - transcript quantification from RNA-seq data3
- [impute](https://imputationserver.sph.umich.edu/index.html) imputation server
- [gatk](https://gatk.broadinstitute.org/hc/en-us) - genome analysis toolkit
- [conda](https://docs.conda.io/en/latest/) - environment management
- [slurm](https://slurm.schedmd.com/documentation.html) - workload management
- [nfcore](https://nf-co.re/) - Easy to use bfx analysis pipelines built using Nextflow
