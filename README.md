# digitalResilienceofYouth
This repository contains the data and code used to generate several of the analyses in this paper. Analysis are conducted in R (version 4.4.1) and Rstudio (version 2024.04.2+764).

There are two files included in this repository, one is the “Supplementals.Rmd” file and the other “supplemental_data.RData” file. The RMarkdown file includes the code used to complete the two-mode network of the risks and platforms as presented in Figure 3. The files generate the t-test results for the comparison of men’s and women’s preferences for a greater number, no change, or a fewer number of parental controls. The files will also generate plots and statistical summaries for the Bayes factor analysis of the number of parental controls by highest educational level and gender and number of parental controls by income level and gender.  The RData file includes the data.  

If you would like to run these analyses on your own computer, then you will need to download both the RMarkdown file and the RData file and import them into RStudio using the load workspace button in the environment.  Once you have the RMarkdown imported, then you are ready to begin running the code.

You may be prompted to install some packages if you do not already have them installed.  R will prompt you on which ones once you attempt to run the code.  To do so you will need to use the function install.packages() and include the package in the parenthesis inside of quotes.  
