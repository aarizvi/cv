## My pagedown rendered CV

This repo is forked from Nick Stayers resume builder repo.

This repo contains the source-code and results of my CV built with the [pagedown package](https://pagedown.rbind.io) and a modified version of the 'resume' template. 

The main files are:

- `index.Rmd`: Source template for the cv, contains a variable `PDF_EXPORT` in the header that changes styles for pdf vs html. 
- `index.html`: The final output of the template when the header variable `PDF_EXPORT` is set to `FALSE`. View it at [abbasrizvi.com/cv](http://abbasrizvi.com/cv).
- `resume.Rmd`: Source template for single page resume. 
- `abbas_rizvi_resume.pdf`: Result for single page resume.
- `positions.csv`: A csv with columns encoding the various fields needed for a position entry in the CV. A column `section` is also available so different sections know which rows to use.
- `css/`: Directory containing the custom CSS files used to tweak the default 'resume' format from pagedown. 

