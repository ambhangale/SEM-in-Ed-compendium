# USE ME

This file contains some notes on how to work with bookdown and how to edit/contribute to this project.

## What this repo contains.

This repository holds, among other things, RMarkdown scripts that contain learning materials for the graduate level course 'Structural Equation Modeling in Education', 
as a part of the Research Master program of the Research Institute of Child Development and Education.

This content can be rendered into a 'gitbook' interactive book using the RStudio IDE. 
This requires the 'bookdown' package to be installed. 
When an 'index' file is present that contains the appropriate configuration in a YAML header, the book can be built using the 'Build Book' button.
Rstudio then proceeds to Merge and Knit (or Knit and Merge, depending on the config) the 'index' file and, subsequently, all '.Rmd' files in alphabetical order.

## Some considerations in generating and editing chapters for the book.

- YAML headers
- TikZ and/or latex chunks
    - R chunk with {engine='tikz', fig.path='images/tikz/'}
    - see Ch 12 & 27 examples
    - Save standard R plots to fig.path='images/R/'
- headings structure
- chunk labels
- 
