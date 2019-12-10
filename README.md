# plsc31101-final-project
Final project for Computational tools
Description

This project uses ggplot2 to compare election data for national and state elections in India, to see if people vote for different parties depending on the level of legislature that elections are being held for. This is done through a study of 2 Indian states- Karnataka and Kerala- for the national and state elections between 2009 to 2019.

This is visualized by using ggplot2 to create dodge bar plots and donut charts, to show the percentage of seats won by a party and the aggregate number of seats won by a party in both states, for all elections under consideration. The ggpubr package was used to then present the donut charts for each state in the form of a grid, for easy visualization.

Dependencies

R version 3.6.1
R packages used- tidyverse, ggplot2, ggpubr, purrr, stringr
Files

Narrative.rmd- Provides a 3 page narrative of the objectives of the project, the computational challenge faced, the alternative developed and possibilities for future work.
Narrative.pdf- A knitted file of Narrative.rmd
ppt_final_project.pptx- slides for the lightning talk session
Code

Karnataka elections- Creates the grid of donut charts and the dodged bar plot for the election results of Karnataka. Kerala elections- Creates the grid of donut charts and the dodged bar plot for the election results of Kerala

Data

The data has been manually cleaned due to the unsuitability of using R to do the same. The data contains the election result by constituency for Kerala and Karnataka for all the election years under review.

Karnataka:

2009_karnataka - the party that won in each constituency in the national election

2013_karnataka- the party that won in each constituency in the state election

2014_karnataka- the party that won in each constituency in the national election

2018_karnataka- the party that won in each constituency in the state election

2019_karnataka- the party that won in each constituency in the national election

Kerala:

2009_kerala- the party that won in each constituency in the national election

2011_kerala- the party that won in each constituency in the state election

2014_kerala- the party that won in each constituency in the national election

2016_kerala- the party that won in each constituency in the state election

2019_kerala- the party that won in each constituency in the national election

Results

Karnataka elections- the dodged bar plot for state and national elections held in Karnataka showing the percentage of seats won by political parties in different elections

Karnataka pie- charts- the grid of donut charts representing the number of seats won by political parties in Karnataka for elections between 2009- 2019

Kerala elections- the dodged bar plot for state and national elections held in Kerala showing the percentage of seats won by political parties in different elections

Kerala pie- charts- the grid of donut charts representing the number of seats won by political parties in Kerala for elections between 2009- 2019