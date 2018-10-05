
# Analysing Campylobacter time series in R

This is the repository for the Epiconcept case study on interrupted time series using *R* statistical programming software. 

The following files are included: 

- *EpiconceptCampyTSA.Rmd*: an R-markdown file which has all the text and analysis script for the case study. This uses the "worded" package for styling word documents (mostly for being able to insert page breaks) - which can be installed using devtools::install_github("davidgohel/worded"). The package is loaded at the of the markdown script within the r setup code-chunk.
  - In order for this to work you will require [Pandoc](https://pandoc.org/installing.html) and also a LaTeX processor such as [MiKTeX](https://miktex.org/download). 
- *README.md*: a markdown file that is used to create this introductory text for the git-hub repository. 
- *LICENSE.md*: a markdown file that is used to create a license for the git-hub repository. 
- *EpiconceptCampTSA.Rproj*: an R project required for being able to push scripts up on to git-hub. 
- *.gitignore*: required for the initiation of git repositories. 