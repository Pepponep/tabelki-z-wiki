# tabelki-z-wiki - województwa
library(tidyverse)
library(rvest)
library(glue)
library(stringr)
library(lubridate)
library(knitr)
library(kableExtra

# jaką stronę wczytujemy?
base_url <- "https://pl.wikipedia.org/wiki/Wojew%C3%B3dztwo"
 
# no to wczytujemy!
page <- read_html(base_url)
