# UHG-Capstone
This is a shared repository for Group 5's capstone project for the CMU SURE UHG Bridges to Healthcare Summer 2025 program

library(tidyverse)

install.packages("corrr")
library(corrr)

library(readr)        # tidyverse reader
library(janitor)      # optional, for nicer names

#this is what I'm calling the dataset... i also deleted the row from Excel instead of R
child_data1 <- analytic_data2025_v3
glimpse(child_data1)
