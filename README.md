Rolling Data Sales - examine housing sales data set of Brooklyn
===============================================================

Project Purpose
---------------

Using the Rolling Data Sales website, download and examine housing sales data set of Brooklyn. This include cleansing of the data and then analyse it.

Project Folder and File structure
---------------------------------

-   Folders:-

1.  Source Directory:- This folder contains the R source code used to analyze the Rolling Sales Data.

2.  <Data:-> This folder contains the original data downloaded from the Rolling Data Sales website.

3.  Paper:- This folder contains file that explains the result of the analysis and information regarding any meaningful pattern observed during analysis.

-   Files:-

1.  source/R\_rollingsales\_brooklyn.R:- R code that reads the dataset present in the data folder and perfrom analysis on it.

2.  data/rollingsales\_brooklyn.xls:- The original data file downloaded from the Rolling Data Sales website.

3.  data/rollingsales\_brooklyn.csv:- The csv data file generated from the original downloaded file from the Rolling Data Sales website. ONly the type of the file changed, no other changes made.

4.  paper/patterns.md:- This file contains the result of the analysis and information regarding meaningful patterns observed during analysis.

5.  README.md:- This file includes an explanation of the purpose of the project and the other files.

Session Information
===================

    ## R version 3.3.2 (2016-10-31)
    ## Platform: x86_64-w64-mingw32/x64 (64-bit)
    ## Running under: Windows 10 x64 (build 14393)
    ## 
    ## locale:
    ## [1] LC_COLLATE=English_Canada.1252  LC_CTYPE=English_Canada.1252   
    ## [3] LC_MONETARY=English_Canada.1252 LC_NUMERIC=C                   
    ## [5] LC_TIME=English_Canada.1252    
    ## 
    ## attached base packages:
    ## [1] stats     graphics  grDevices utils     datasets  methods   base     
    ## 
    ## loaded via a namespace (and not attached):
    ##  [1] backports_1.0.4 magrittr_1.5    rprojroot_1.1   tools_3.3.2    
    ##  [5] htmltools_0.3.5 yaml_2.1.14     Rcpp_0.12.8     stringi_1.1.2  
    ##  [9] rmarkdown_1.3   knitr_1.15.1    stringr_1.1.0   digest_0.6.10  
    ## [13] evaluate_0.10
