# Tidy Tuesday

A weekly social data project in R, the base repo is [HERE](https://github.com/rfordatascience/tidytuesday) and maintaned by [Tom Mock](https://themockup.blog/) (his Blog)

A weekly data project aimed at the R ecosystem. As this project was borne out of the R4DS Online Learning Community and the R for Data Science textbook, an emphasis was placed on understanding how to summarize and arrange data to make meaningful charts with ggplot2, tidyr, dplyr, and other tools in the tidyverse ecosystem. However, any code-based methodology is welcome - just please remember to share the code used to generate the results.

Nice package to download the weekly data is maintained by [thebioengineer](https://github.com/thebioengineer/tidytuesdayR)

`#install.packages("devtools")`  
`devtools::install_github("thebioengineer/tidytuesdayR")`

## usage

`library(tidytuesdayR)`  
`tt_data <- tt_load("2019-01-15")`

or

`tt_data <- tt_load(2019, week=3)`
