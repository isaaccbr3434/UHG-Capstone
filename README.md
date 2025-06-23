# UHG-Capstone
This is a shared repository for Group 5's capstone project for the CMU SURE UHG Bridges to Healthcare Summer 2025 program

library(tidyverse)

install.packages("corrr")
library(corrr)
# load data
child_data <- analytic_data2025_v2_csv

library(readr)        # tidyverse reader
library(janitor)      # optional, for nicer names

child_data1 <- analytic_data2025_v3
glimpse(child_data1)
