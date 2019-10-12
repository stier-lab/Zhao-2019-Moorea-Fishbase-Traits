# Zhao-2019-Moorea-Fishbase-Traits 
*i.e. pulling trait data for Moorea Coral Reef LTER species from Fishbase 

This  is the README file for the pulling traits for each of the species seen on fish abundance LTER Moorea Coral Reef Survey data. 

Trait data for Moorea fish species were pulled from Fishbase using  using the rfishbase package 


To see how the rfishbase package works see these pdfs:

see https://ropensci.org/pdfs/rfishbase.pdf and https://cran.r-project.org/web/packages/rfishbase/rfishbase.pdf


There is data available on each of the files created using the fishbase Manual. Below are the links to some of the pages of the manual that relate to the datasets created:

ecosystem_Moorea:
fishbase.org/manual/FishBaseThe_ECOLOGY_Table.htm

ecology_Moorea:
https://www.fishbase.se/manual/english/fishbasethe_ecology_table.htm

trophic_Moorea:

fooditems_Moorea:
https://www.fishbase.de/manual/english/fishbasethe_diet_table.htm

maturity_Moorea:

popgrowth_Moorea:

predators_Moorea:
#https://www.fishbase.in/manual/english/fishbasethe_predators_table.htm

morphology_Moorea"

# Code

file name | description 
---|-----------
MR_firesting_v1_1.R | Written by Krista Kraskura (GitHub: [@kraskura](https://github.com/kraskura)) to analyze FireStingO2 data. This converts raw .txt files into usable .csv files, generates raw data slopes for each measurement cycle throughout a trial, calculates MMR, SMR, AS, and EPOC. Must be sourced prior to working with raw data (in 1_MR_data_processing.Rmd, X_blank_processing).
1_MR_lobster_processing.Rmd | This script uses MR_firesting_v1_1.R to convert FireSting data into a usable format for analyses. It (a) converts raw data .txt files (generated by FireSting) to .csv files, (b) processes manual files (files from which MMR will be calculated), (c) processes auto files (files from which SMR will be calculated), (d) calculates SMR, MMR, AS, and EPOC. Data files and plots generated here can be used for creating finalized plots and running statistical analyses.
