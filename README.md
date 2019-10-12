# Zhao-2019-Moorea-Fishbase-Traits 
*i.e. pulling trait data for Moorea Coral Reef LTER species from Fishbase*

This  is the README file for the pulling traits for each of the species seen on fish abundance LTER Moorea Coral Reef Survey data. 

    Trait data for Moorea fish species were pulled from Fishbase using  using the rfishbase package 


To see how the rfishbase package works see these pdfs:
see https://ropensci.org/pdfs/rfishbase.pdf and 
https://cran.r-project.org/web/packages/rfishbase/rfishbase.pdf


There is data available on each of the files created using the fishbase Manual. Below are the links to some of the pages of the manual that relate to the datasets created:

ecosystem_Moorea: fishbase.org/manual/FishBaseThe_ECOLOGY_Table.htm

ecology_Moorea: https://www.fishbase.se/manual/english/fishbasethe_ecology_table.htm

fooditems_Moorea: https://www.fishbase.de/manual/english/fishbasethe_diet_table.htm

predators_Moorea: https://www.fishbase.in/manual/english/fishbasethe_predators_table.htm



additional datasets created are:
    trophic_Moorea
    maturity_Moorea
    popgrowth_Moorea
    morphology_Moorea

# Code

file name | description 
---|-----------
MCR_Taxon_clean.csv| A cleaned up list of the fish species seen during LTER Moorea Coral Reef visual surveys. What has been removed from this list as compared to that available on the NSF LTER MCR website are the 'unidentified'species of a particular taxon. 
fb.Rmd |This markdown file uses the rfishbase package to create pull data from fishbase. These data are pulled by fishbase page and the code produces the datasets (.csv) described above.  
