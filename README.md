# EDCs_GAA
EDC exposures and gestational age acceleration 

#─ Session info ────────────────────────────────────────────────────────────────────────────────────────────────────────
 setting  value
 version  R version 4.2.2 (2022-10-31)
 os       macOS 26.1
 system   x86_64, darwin17.0
 ui       RStudio
 language (EN)
 collate  en_US.UTF-8
 ctype    en_US.UTF-8
 tz       America/New_York
 date     2025-12-10
 rstudio  2025.09.2+418 Cucumberleaf Sunflower (desktop)
 pandoc   3.6.3 @ /Applications/RStudio.app/Contents/Resources/app/quarto/bin/tools/x86_64/ (via rmarkdown)
 quarto   1.7.32 @ /Applications/RStudio.app/Contents/Resources/app/quarto/bin/quarto

─ Packages ────────────────────────────────────────────────────────────────────────────────────────────────────────────
 package                                       * version    date (UTC) lib source
 abind                                           1.4-8      2024-09-12 [1] CRAN (R 4.2.2)
 affy                                            1.76.0     2022-11-01 [1] Bioconductor
 affyio                                          1.68.0     2022-11-01 [1] Bioconductor
 annotate                                        1.76.0     2022-11-01 [1] Bioconductor
 AnnotationDbi                                 * 1.60.2     2023-03-10 [1] Bioconductor
 AnnotationForge                                 1.40.2     2023-03-27 [1] Bioconductor
 AnnotationHub                                   3.6.0      2022-11-01 [1] Bioconductor
 AnnotationHubData                               1.28.0     2022-11-01 [1] Bioconductor
 archive                                         1.1.7      2023-12-11 [1] CRAN (R 4.2.0)
 askpass                                         1.2.0      2023-09-03 [1] CRAN (R 4.2.0)
 backports                                       1.4.1      2021-12-13 [1] CRAN (R 4.2.0)
 base64                                          2.0.2      2024-10-04 [1] CRAN (R 4.2.2)
 beanplot                                        1.3.1      2022-04-09 [1] CRAN (R 4.2.0)
 Biobase                                       * 2.58.0     2022-11-01 [1] Bioconductor
 BiocCheck                                       1.34.3     2023-03-03 [1] Bioconductor
 BiocFileCache                                   2.6.1      2023-02-17 [1] Bioconductor
 BiocGenerics                                  * 0.44.0     2022-11-01 [1] Bioconductor
 BiocIO                                          1.8.0      2022-11-01 [1] Bioconductor
 BiocManager                                     1.30.27    2025-11-14 [1] CRAN (R 4.2.2)
 BiocParallel                                  * 1.32.6     2023-03-17 [1] Bioconductor
 BiocVersion                                     3.16.0     2022-05-05 [1] Bioconductor
 biocViews                                       1.66.3     2023-03-06 [1] Bioconductor
 biomaRt                                         2.54.1     2023-03-20 [1] Bioconductor
 Biostrings                                    * 2.66.0     2022-11-01 [1] Bioconductor
 bit                                             4.0.5      2022-11-15 [1] CRAN (R 4.2.0)
 bit64                                           4.0.5      2020-08-30 [1] CRAN (R 4.2.0)
 bitops                                          1.0-7      2021-04-24 [1] CRAN (R 4.2.0)
 blob                                            1.2.4      2023-03-17 [1] CRAN (R 4.2.0)
 broom                                           1.0.11     2025-12-04 [1] CRAN (R 4.2.2)
 bumphunter                                    * 1.40.0     2022-11-01 [1] Bioconductor
 cachem                                          1.0.8      2023-05-01 [1] CRAN (R 4.2.0)
 car                                             3.1-3      2024-09-27 [1] CRAN (R 4.2.2)
 carData                                         3.0-5      2022-01-06 [1] CRAN (R 4.2.0)
 cli                                             3.6.2      2023-12-11 [1] CRAN (R 4.2.0)
 cluster                                       * 2.1.6      2023-12-01 [1] CRAN (R 4.2.0)
 codetools                                       0.2-20     2024-03-31 [1] CRAN (R 4.2.2)
 colorspace                                      2.1-0      2023-01-23 [1] CRAN (R 4.2.0)
 crayon                                          1.5.3      2024-06-20 [1] CRAN (R 4.2.2)
 curl                                            5.2.0      2023-12-08 [1] CRAN (R 4.2.0)
 data.table                                      1.14.10    2023-12-08 [1] CRAN (R 4.2.0)
 DBI                                             1.2.3      2024-06-02 [1] CRAN (R 4.2.2)
 dbplyr                                          2.3.4      2023-09-26 [1] CRAN (R 4.2.2)
 DelayedArray                                    0.24.0     2022-11-01 [1] Bioconductor
 DelayedMatrixStats                              1.20.0     2022-11-01 [1] Bioconductor
 devtools                                      * 2.4.5      2022-10-11 [1] CRAN (R 4.2.0)
 dichromat                                       2.0-0.1    2022-05-02 [1] CRAN (R 4.2.0)
 digest                                          0.6.33     2023-07-07 [1] CRAN (R 4.2.0)
 doRNG                                           1.8.6.2    2025-04-02 [1] CRAN (R 4.2.2)
 dplyr                                         * 1.1.4      2023-11-17 [1] CRAN (R 4.2.2)
 dynamicTreeCut                                  1.63-1     2016-03-11 [1] CRAN (R 4.2.0)
 edgeR                                           3.40.2     2023-01-19 [1] Bioconductor
 ellipsis                                        0.3.2      2021-04-29 [1] CRAN (R 4.2.0)
 evaluate                                        1.0.5      2025-08-27 [1] CRAN (R 4.2.2)
 ExperimentHub                                   2.6.0      2022-11-01 [1] Bioconductor
 ExperimentHubData                               1.24.0     2022-11-01 [1] Bioconductor
 farver                                          2.1.1      2022-07-06 [1] CRAN (R 4.2.0)
 fastmap                                         1.1.1      2023-02-24 [1] CRAN (R 4.2.0)
 FDb.InfiniumMethylation.hg19                  * 2.2.0      2023-06-05 [1] Bioconductor
 filelock                                        1.0.3      2023-12-11 [1] CRAN (R 4.2.0)
 forcats                                       * 1.0.1      2025-09-25 [1] CRAN (R 4.2.2)
 foreach                                       * 1.5.2      2022-02-02 [1] CRAN (R 4.2.0)
 formatR                                         1.14       2023-01-17 [1] CRAN (R 4.2.0)
 Formula                                         1.2-5      2023-02-24 [1] CRAN (R 4.2.0)
 fs                                              1.6.3      2023-07-20 [1] CRAN (R 4.2.0)
 futile.logger                                 * 1.4.3      2016-07-10 [1] CRAN (R 4.2.0)
 futile.options                                  1.0.1      2018-04-20 [1] CRAN (R 4.2.0)
 genefilter                                    * 1.80.3     2023-01-19 [1] Bioconductor
 generics                                        0.1.4      2025-05-09 [1] CRAN (R 4.2.2)
 GenomeInfoDb                                  * 1.34.9     2023-02-02 [1] Bioconductor
 GenomeInfoDbData                                1.2.9      2023-03-30 [1] Bioconductor
 GenomicAlignments                               1.34.1     2023-03-09 [1] Bioconductor
 GenomicFeatures                               * 1.50.4     2023-01-24 [1] Bioconductor
 GenomicRanges                                 * 1.50.2     2022-12-16 [1] Bioconductor
 GEOquery                                        2.66.0     2022-11-01 [1] Bioconductor
 ggplot2                                       * 3.5.1      2024-04-23 [1] CRAN (R 4.2.2)
 ggpmisc                                         0.5.5      2023-11-15 [1] CRAN (R 4.2.0)
 ggpp                                            0.5.9      2025-06-28 [1] CRAN (R 4.2.2)
 ggpubr                                          0.6.0      2023-02-10 [1] CRAN (R 4.2.0)
 ggsignif                                        0.6.4      2022-10-13 [1] CRAN (R 4.2.0)
 glue                                            1.6.2      2022-02-24 [1] CRAN (R 4.2.0)
 graph                                           1.76.0     2022-11-01 [1] Bioconductor
 gridExtra                                       2.3        2017-09-09 [1] CRAN (R 4.2.0)
 gtable                                          0.3.6      2024-10-25 [1] CRAN (R 4.2.2)
 HDF5Array                                       1.26.0     2022-11-01 [1] Bioconductor
 hms                                             1.1.4      2025-10-17 [1] CRAN (R 4.2.2)
 htmltools                                       0.5.7      2023-11-03 [1] CRAN (R 4.2.0)
 htmlwidgets                                     1.6.4      2023-12-06 [1] CRAN (R 4.2.0)
 httpuv                                          1.6.13     2023-12-06 [1] CRAN (R 4.2.0)
 httr                                            1.4.7      2023-08-15 [1] CRAN (R 4.2.0)
 IlluminaHumanMethylation450kanno.ilmn12.hg19  * 0.6.1      2023-06-05 [1] Bioconductor
 IlluminaHumanMethylation450kmanifest          * 0.4.0      2023-06-05 [1] Bioconductor
 IlluminaHumanMethylationEPICanno.ilm10b4.hg19 * 0.6.0      2023-06-05 [1] Bioconductor
 illuminaio                                    * 0.40.0     2022-11-01 [1] Bioconductor
 impute                                          1.72.3     2023-01-19 [1] Bioconductor
 interactiveDisplayBase                          1.36.0     2022-11-01 [1] Bioconductor
 IRanges                                       * 2.32.0     2022-11-01 [1] Bioconductor
 iterators                                     * 1.0.14     2022-02-05 [1] CRAN (R 4.2.0)
 janitor                                       * 2.2.1      2024-12-22 [1] CRAN (R 4.2.2)
 jsonlite                                        1.8.8      2023-12-04 [1] CRAN (R 4.2.0)
 KEGGREST                                        1.38.0     2022-11-01 [1] Bioconductor
 KernSmooth                                      2.23-22    2023-07-10 [1] CRAN (R 4.2.0)
 knitr                                           1.45       2023-10-30 [1] CRAN (R 4.2.2)
 lambda.r                                        1.2.4      2019-09-18 [1] CRAN (R 4.2.0)
 later                                           1.3.2      2023-12-06 [1] CRAN (R 4.2.0)
 lattice                                         0.22-5     2023-10-24 [1] CRAN (R 4.2.0)
 lifecycle                                       1.0.4      2023-11-07 [1] CRAN (R 4.2.2)
 limma                                         * 3.54.2     2023-02-28 [1] Bioconductor
 locfit                                        * 1.5-9.8    2023-06-11 [1] CRAN (R 4.2.0)
 lubridate                                     * 1.9.3      2023-09-27 [1] CRAN (R 4.2.0)
 lumi                                          * 2.50.0     2022-11-01 [1] Bioconductor
 magrittr                                        2.0.3      2022-03-30 [1] CRAN (R 4.2.0)
 MASS                                            7.3-60.0.1 2024-01-13 [1] CRAN (R 4.2.2)
 Matrix                                          1.6-4      2023-11-30 [1] CRAN (R 4.2.0)
 MatrixGenerics                                * 1.10.0     2022-11-01 [1] Bioconductor
 MatrixModels                                    0.5-4      2025-03-26 [1] CRAN (R 4.2.2)
 matrixStats                                   * 1.2.0      2023-12-11 [1] CRAN (R 4.2.0)
 mclust                                          6.0.1      2023-11-15 [1] CRAN (R 4.2.0)
 memoise                                         2.0.1      2021-11-26 [1] CRAN (R 4.2.0)
 methylclock                                   * 1.4.0      2022-11-01 [1] Bioconductor
 methylclockData                               * 1.6.0      2022-11-03 [1] Bioconductor
 methylumi                                     * 2.44.0     2022-11-01 [1] Bioconductor
 mgcv                                          * 1.9-1      2023-12-21 [1] CRAN (R 4.2.0)
 mime                                            0.12       2021-09-28 [1] CRAN (R 4.2.0)
 minfi                                         * 1.44.0     2022-11-01 [1] Bioconductor
 miniUI                                          0.1.2      2025-04-17 [1] CRAN (R 4.2.2)
 multtest                                        2.54.0     2022-11-01 [1] Bioconductor
 nleqslv                                         3.3.5      2023-11-26 [1] CRAN (R 4.2.0)
 nlme                                          * 3.1-164    2023-11-27 [1] CRAN (R 4.2.0)
 nor1mix                                         1.3-3      2024-04-06 [1] CRAN (R 4.2.2)
 openssl                                         2.1.1      2023-09-25 [1] CRAN (R 4.2.0)
 org.Hs.eg.db                                  * 3.16.0     2023-06-05 [1] Bioconductor
 OrganismDbi                                     1.40.0     2022-11-01 [1] Bioconductor
 pacman                                        * 0.5.1      2019-03-11 [1] CRAN (R 4.2.0)
 PerformanceAnalytics                            2.0.4      2020-02-06 [1] CRAN (R 4.2.0)
 pillar                                          1.11.1     2025-09-17 [1] CRAN (R 4.2.2)
 pkgbuild                                        1.4.8      2025-05-26 [1] CRAN (R 4.2.2)
 pkgconfig                                       2.0.3      2019-09-22 [1] CRAN (R 4.2.0)
 pkgload                                         1.4.1      2025-09-23 [1] CRAN (R 4.2.2)
 plyr                                            1.8.9      2023-10-02 [1] CRAN (R 4.2.0)
 png                                             0.1-8      2022-11-29 [1] CRAN (R 4.2.0)
 polynom                                         1.4-1      2022-04-11 [1] CRAN (R 4.2.0)
 preprocessCore                                  1.60.2     2023-01-19 [1] Bioconductor
 prettyunits                                     1.2.0      2023-09-24 [1] CRAN (R 4.2.0)
 profvis                                         0.3.8      2023-05-02 [1] CRAN (R 4.2.0)
 progress                                        1.2.3      2023-12-06 [1] CRAN (R 4.2.0)
 promises                                        1.2.1      2023-08-10 [1] CRAN (R 4.2.0)
 purrr                                         * 1.0.2      2023-08-10 [1] CRAN (R 4.2.0)
 quadprog                                      * 1.5-8      2019-11-20 [1] CRAN (R 4.2.0)
 quantreg                                        5.97       2023-08-19 [1] CRAN (R 4.2.0)
 R6                                              2.6.1      2025-02-15 [1] CRAN (R 4.2.2)
 rappdirs                                        0.3.3      2021-01-31 [1] CRAN (R 4.2.0)
 RBGL                                            1.74.0     2022-11-01 [1] Bioconductor
 RColorBrewer                                    1.1-3      2022-04-03 [1] CRAN (R 4.2.0)
 Rcpp                                            1.0.11     2023-07-06 [1] CRAN (R 4.2.0)
 RCurl                                           1.98-1.13  2023-11-02 [1] CRAN (R 4.2.0)
 readr                                         * 2.1.4      2023-02-10 [1] CRAN (R 4.2.0)
 remotes                                         2.5.0      2024-03-17 [1] CRAN (R 4.2.2)
 reshape                                         0.8.10     2025-06-19 [1] CRAN (R 4.2.2)
 reshape2                                      * 1.4.4      2020-04-09 [1] CRAN (R 4.2.0)
 restfulr                                        0.0.15     2022-06-16 [1] CRAN (R 4.2.0)
 rhdf5                                           2.42.1     2023-04-07 [1] Bioconductor
 rhdf5filters                                    1.10.1     2023-03-24 [1] Bioconductor
 Rhdf5lib                                        1.20.0     2022-11-01 [1] Bioconductor
 rjson                                           0.2.21     2022-01-09 [1] CRAN (R 4.2.0)
 rlang                                           1.1.2      2023-11-04 [1] CRAN (R 4.2.0)
 rmarkdown                                       2.30       2025-09-28 [1] CRAN (R 4.2.2)
 rngtools                                        1.5.2      2021-09-20 [1] CRAN (R 4.2.0)
 ROC                                           * 1.74.0     2022-11-01 [1] Bioconductor
 RPMM                                          * 1.25       2017-02-28 [1] CRAN (R 4.2.0)
 Rsamtools                                       2.14.0     2022-11-01 [1] Bioconductor
 rsconnect                                       1.7.0      2025-12-06 [1] CRAN (R 4.2.2)
 RSQLite                                         2.3.4      2023-12-08 [1] CRAN (R 4.2.0)
 rstatix                                         0.7.3      2025-10-18 [1] CRAN (R 4.2.2)
 rstudioapi                                      0.17.1     2024-10-22 [1] CRAN (R 4.2.2)
 rtracklayer                                     1.58.0     2022-11-01 [1] Bioconductor
 RUnit                                           0.4.33.1   2025-06-17 [1] CRAN (R 4.2.2)
 S4Vectors                                     * 0.36.2     2023-02-26 [1] Bioconductor
 scales                                        * 1.4.0      2025-04-24 [1] CRAN (R 4.2.2)
 scrime                                          1.3.5      2018-12-01 [1] CRAN (R 4.2.0)
 sessioninfo                                     1.2.3      2025-02-05 [1] CRAN (R 4.2.2)
 shiny                                           1.9.1      2024-08-01 [1] CRAN (R 4.2.2)
 siggenes                                        1.72.0     2022-11-01 [1] Bioconductor
 snakecase                                       0.11.1     2023-08-27 [1] CRAN (R 4.2.0)
 SparseM                                         1.81       2021-02-18 [1] CRAN (R 4.2.0)
 sparseMatrixStats                               1.10.0     2022-11-01 [1] Bioconductor
 stringdist                                      0.9.12     2023-11-28 [1] CRAN (R 4.2.0)
 stringi                                         1.8.3      2023-12-11 [1] CRAN (R 4.2.0)
 stringr                                       * 1.6.0      2025-11-04 [1] CRAN (R 4.2.2)
 SummarizedExperiment                          * 1.28.0     2022-11-01 [1] Bioconductor
 survival                                        3.5-7      2023-08-14 [1] CRAN (R 4.2.0)
 sva                                           * 3.46.0     2022-11-01 [1] Bioconductor
 tibble                                        * 3.2.1      2023-03-20 [1] CRAN (R 4.2.0)
 tidyr                                         * 1.3.1      2024-01-24 [1] CRAN (R 4.2.2)
 tidyselect                                      1.2.1      2024-03-11 [1] CRAN (R 4.2.2)
 tidyverse                                     * 2.0.0      2023-02-22 [1] CRAN (R 4.2.0)
 timechange                                      0.3.0      2024-01-18 [1] CRAN (R 4.2.2)
 TxDb.Hsapiens.UCSC.hg19.knownGene             * 3.2.2      2023-06-05 [1] Bioconductor
 tzdb                                            0.4.0      2023-05-12 [1] CRAN (R 4.2.0)
 urlchecker                                      1.0.1      2021-11-30 [1] CRAN (R 4.2.0)
 usethis                                       * 3.2.1      2025-09-06 [1] CRAN (R 4.2.2)
 vctrs                                           0.6.5      2023-12-01 [1] CRAN (R 4.2.0)
 vroom                                           1.6.5      2023-12-05 [1] CRAN (R 4.2.0)
 wateRmelon                                    * 2.4.0      2022-11-01 [1] Bioconductor
 withr                                           3.0.2      2024-10-28 [1] CRAN (R 4.2.2)
 xfun                                            0.41       2023-11-01 [1] CRAN (R 4.2.0)
 XML                                             3.99-0.16  2023-11-29 [1] CRAN (R 4.2.0)
 xml2                                            1.3.6      2023-12-04 [1] CRAN (R 4.2.0)
 xtable                                          1.8-4      2019-04-21 [1] CRAN (R 4.2.0)
 xts                                             0.13.1     2023-04-16 [1] CRAN (R 4.2.0)
 XVector                                       * 0.38.0     2022-11-01 [1] Bioconductor
 yaml                                            2.3.8      2023-12-11 [1] CRAN (R 4.2.0)
 zlibbioc                                        1.44.0     2022-11-01 [1] Bioconductor
 zoo                                             1.8-12     2023-04-13 [1] CRAN (R 4.2.0)