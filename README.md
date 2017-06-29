# geneScrapeR

geneScrapeR is an R package that mines NCBI databases for genes mentioned in connection with diseases and other medical conditions. It counts the number of articles that mention each gene cited and returns them in a data frame. 

### Motivation

geneScrapeR is meant to make it easy to extract the genes mentioned in articles available in NCBI databases. It returns them in a format that is easy to use and read.

### Installation

If you do not have a package that geneScrapeR depends on you may get an error as geneScrapeR installs. Before being able to successfully install geneScrapeR you will have to install the missing package separately. After installing all of the packages that geneScrapeR depends on you will be able to successfully install geneScrapeR.

To install geneScrapeR
```r
devtools::install_github('Evatar/geneScrapeR')
```
