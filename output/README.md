# README.md: Output Folder
This directory is the `output` folder for `Mini-Data-Analysis-2`(Milestone 2) and contains outputs generated from `mini-project-2.Rmd` in RStudio with the `knitr` package. Note that there is no output folder for `Mini-Data-Analysis-1`

## Files
#### README.md
The `README` file for this directory that you are currently reading. 

#### cancer_summary.csv
This `.csv` file contains the summarized dataframe used for the majority of the analysis in Milestone 2. You can choose to download this file separately; however, running the code in `Mini-Data-Analysis-2/mini-project-2.Rmd` will also produce an identical output .csv file. 

#### task3_obj.rds
This `.rds` file contains a model object generated from `mini-project-2.Rmd`. Specifically, this is a t-test object performed to determine statistical significance between area means between benign and malignant tumour diagnosis groups. 

## Interacting with this Directory
Files in this directory can be downloaded as outlined in the top level `README.md` by cloning this repository in RStudio. Alternatively, these files can be downloaded onto a local server and loaded into R using the `read_csv()` command from the `readr` package or with the `readRDS()` command from base R. 
