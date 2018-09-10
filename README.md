# JKM
Assignment 2 Techlab


For our Assignment

# Uploading code to use for assignment, DM if the code should be changed further 

setwd("/Users/jacksont/Downloads")


library(tidyverse)
library(lubridate)
library(dplyr)

employment <- read_csv("DP_LIVE_07092018072205440.csv")

read_csv("DP_LIVE_07092018072205440.csv")

unite(employment, Type, MEASURE, INDICATOR) 


# use arrange(employment, TIME) for 10 year span of foreign born population
# employment rates- for 1 ggplot graph
# Use unite() for combined Type of 10 year in each country

# arrange(employment, TIME)
