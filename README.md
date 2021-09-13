# Testing how rmarkdown parses reference lists

From Rstudio you can compile the `.Rmd` file and there is an `http://` link in the reference list. Its result can be seen in `test_windows.html`. If you do the same from Debian (WSL)
```
Rscript -e "rmarkdown::render('test.Rmd')"
```
you dont get a link. However, this is flagged when submitting on CRAN.
