library(RSelenium) # for navigating the web
library(netstat) # for free port
library(dplyr) # general data work
library(readr) # for importing/exporting csv
library(pagedown) # to convert html to pdf
library(kableExtra) # for tables in r markdown
library(lubridate) # for the ymd function on "2. Gather and Filter"

library(readxl) # for EIOPA QA



out_name <- "webpage"
output_folder <- "./output"
r_markdown_link <- "./code/webpage.Rmd"

rmarkdown::render(r_markdown_link,
                  output_dir = output_folder,
                  output_file = paste0(out_name))