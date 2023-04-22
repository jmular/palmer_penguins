# r_walkthroughs_and_tutorials
This repository includes tutorials and sample questions I made to help others in my lab with learning general R principles and code they may encounter

Tutorials and Walkthrough Includes: 

1. R_basics_walkthrough_palmer_penguins
- Setting up your environment by installing and loading packages (both from CRAN and from .csv example
  - Getting a sense of your data by using summary(), glimpse(), colnames()
  - Cleaning and coloring your data to prepare for visualizations
  - Using the count() and table() function
  - P-Value (null and alternative hypothesis) and the chisq.test() to see if something is statistically significant

2. ggplot2_walkthrough_palmer_penguins
  - Making plots using geom_jitter(), goem_point(), and geom_smooth(), including seperating using facet_wrap(~)
  - Labeling and Annotating Graphs and other aestetics
  - Quick Note for Other Important R Tools (Functions, If/Then Statements, For Loop)

3. more_ggplot2_walkthrough_diamond_data.rmd
  - Making plots using other ggplot2 features using embedded diamonds dataset within the ggplot2, geom_bar()

Datasets used:
- palmer penguins package (https://allisonhorst.github.io/palmerpenguins/)
- diamonds package (within the tidyverse)
