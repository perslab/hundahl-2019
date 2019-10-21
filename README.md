# 18-Lipe

R notebooks for reproducing the code in Hundahl et al (2019) 

## Usage

1. clone the repository: `git clone --recurse-submodules https://github.com/perslab/hundahl-2019.git'

2. Open pre-process.Rmd and run the code interactively in RStudio to download and preprocess the sc-RNA dataset 

3. Open lipase_plots.Rmd and run the code interactively in Rstudio to generate the plots.

## Session Info

R version 3.5.3 (2019-03-11)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Storage

Matrix products: default
BLAS/LAPACK: /usr/lib64/libopenblas-r0.3.3.so

locale:
 [1] LC_CTYPE=en_US.UTF-8       LC_NUMERIC=C               LC_TIME=en_US.UTF-8        LC_COLLATE=en_US.UTF-8    
 [5] LC_MONETARY=en_US.UTF-8    LC_MESSAGES=en_US.UTF-8    LC_PAPER=en_US.UTF-8       LC_NAME=C                 
 [9] LC_ADDRESS=C               LC_TELEPHONE=C             LC_MEASUREMENT=en_US.UTF-8 LC_IDENTIFICATION=C       

attached base packages:
 [1] splines   stats4    parallel  stats     graphics  grDevices datasets  utils     methods   base     

other attached packages:
 [1] MASS_7.3-51.4   ggsignif_0.6.0  VGAM_1.1-1      cowplot_1.0.0   Matrix_1.2-17   forcats_0.4.0   stringr_1.4.0  
 [8] dplyr_0.8.3     purrr_0.3.2     readr_1.3.1     tidyr_1.0.0     tibble_2.1.3    ggplot2_3.2.1   tidyverse_1.2.1
[15] Seurat_3.1.0    here_0.1       

loaded via a namespace (and not attached):
  [1] Rtsne_0.15          colorspace_1.4-1    ggridges_0.5.1      rprojroot_1.3-2     fs_1.3.1           
  [6] base64enc_0.1-3     rstudioapi_0.10     leiden_0.3.1        listenv_0.7.0       npsurv_0.4-0       
 [11] ggrepel_0.8.1       lubridate_1.7.4     xml2_1.2.2          codetools_0.2-16    R.methodsS3_1.7.1  
 [16] lsei_1.2-0          knitr_1.25          zeallot_0.1.0       jsonlite_1.6        workflowr_1.4.0    
 [21] broom_0.5.2         ica_1.0-2           cluster_2.1.0       png_0.1-7           R.oo_1.22.0        
 [26] uwot_0.1.4          sctransform_0.2.0   compiler_3.5.3      httr_1.4.1          backports_1.1.4    
 [31] assertthat_0.2.1    lazyeval_0.2.2      cli_1.1.0           htmltools_0.3.6     tools_3.5.3        
 [36] rsvd_1.0.2          igraph_1.2.4.1      gtable_0.3.0        glue_1.3.1          RANN_2.6.1         
 [41] reshape2_1.4.3      Rcpp_1.0.2          cellranger_1.1.0    vctrs_0.2.0         gdata_2.18.0       
 [46] ape_5.3             nlme_3.1-141        gbRd_0.4-11         lmtest_0.9-37       xfun_0.9           
 [51] ps_1.3.0            globals_0.12.4      rvest_0.3.4         lifecycle_0.1.0     irlba_2.3.3        
 [56] renv_0.5.0-39       gtools_3.8.1        future_1.14.0       zoo_1.8-6           scales_1.0.0       
 [61] hms_0.5.1           RColorBrewer_1.1-2  yaml_2.2.0          reticulate_1.13     pbapply_1.4-2      
 [66] gridExtra_2.3       stringi_1.4.3       caTools_1.17.1.2    bibtex_0.4.2        Rdpack_0.11-0      
 [71] SDMTools_1.1-221.1  rlang_0.4.0         pkgconfig_2.0.3     bitops_1.0-6        evaluate_0.14      
 [76] lattice_0.20-38     ROCR_1.0-7          labeling_0.3        htmlwidgets_1.3     processx_3.4.1     
 [81] tidyselect_0.2.5    RcppAnnoy_0.0.13    plyr_1.8.4          magrittr_1.5        R6_2.4.0           
 [86] gplots_3.0.1.1      generics_0.0.2      pillar_1.4.2        haven_2.1.1         withr_2.1.2        
 [91] fitdistrplus_1.0-14 survival_2.44-1.1   future.apply_1.3.0  tsne_0.1-3          modelr_0.1.5       
 [96] crayon_1.3.4        KernSmooth_2.23-15  plotly_4.9.0        rmarkdown_1.15      grid_3.5.3         
[101] readxl_1.3.1        data.table_1.12.2   callr_3.3.2         git2r_0.26.1        metap_1.1          
[106] digest_0.6.21       R.utils_2.9.0       RcppParallel_4.4.4  munsell_0.5.0       viridisLite_0.3.0  

A [workflowr][] project.
[workflowr]: https://github.com/jdblischak/workflowr
