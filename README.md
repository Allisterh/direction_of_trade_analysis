# Direction of Trade Analysis

## Purpose
As part of a school project and pure interest, I decided to take some datasets from the IMF (Internation Monetary Fund) and combined them to see if the direction of trade was correlated with economic development metrics.

## Datasets
Although the .rmd file contains greater detail, the main datasets are from the IMF imports, exports, CPI (consumer price index) and financial development index. These sets are available to the public and are very interesting in scope.

## Report
The final report is available as an RMarkdown file as well as an html for compatibility. The RMardown is of slightly more interest for those wishing to replicate the process and make their own changes. I would love to see someone take this project and find more interesting connections or bring their economic knowledge to bear.

## Running the .rmd
The biggest concern in running the RMarkdown file is getting the working directory set up to read the right files. The markdown here contains an old directory structure on a shared machine so it will not work for others. Use the builtin `setwd()` function to set the working directory to the place where this repo is cloned. As long as the whole repo is cloned it should pick up the files.