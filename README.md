# HELLO

This is another line.

Here is a line from GitHub online. Here you need to install `tidyverse`. This is from the course on [Reproducible Coding](https://utrechtuniversity.github.io/workshop-computational-reproducibility/docs/7.2-the-readme-page.html)

## Project organization
- PG = project-generated
- HW = human-writable
- RO = read only

## Notes

For additional notes, please refer to the [`notes.md`](/notes.md) within this repo.

```
.
├── .gitignore
├── CITATION.md
├── LICENSE.md
├── README.md
├── requirements.txt
├── bin                <- Compiled and external code, ignored by git (PG)
│   └── external       <- Any external source code, ignored by git (RO)
├── config             <- Configuration files (HW)
├── data               <- All project data, ignored by git
│   ├── processed      <- The final, canonical data sets for modeling. (PG)
│   ├── raw            <- The original, immutable data dump. (RO)
│   └── temp           <- Intermediate data that has been transformed. (PG)
├── docs               <- Documentation notebook for users (HW)
│   ├── manuscript     <- Manuscript source, e.g., LaTeX, Markdown, etc. (HW)
│   └── reports        <- Other project reports and notebooks (e.g. Jupyter, .Rmd) (HW)
├── results
│   ├── figures        <- Figures for the manuscript or reports (PG)
│   └── output         <- Other output for the manuscript or reports (PG)
└── src                <- Source code for this project (HW)

```


## License

This project is licensed under the terms of the [MIT License](/LICENSE.md)

## sessionInfo()

```
R version 4.2.2 (2022-10-31 ucrt)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 19042)

Matrix products: default

locale:
[1] LC_COLLATE=Dutch_Netherlands.utf8  LC_CTYPE=Dutch_Netherlands.utf8   
[3] LC_MONETARY=Dutch_Netherlands.utf8 LC_NUMERIC=C                      
[5] LC_TIME=Dutch_Netherlands.utf8    

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
[1] TempPackage_1.0 docstring_1.0.0

loaded via a namespace (and not attached):
 [1] roxygen2_7.2.2  withr_2.5.0     rprojroot_2.0.3 R6_2.5.1       
 [5] lifecycle_1.0.3 magrittr_2.0.3  rlang_1.0.6     stringi_1.7.8  
 [9] cli_3.4.1       fs_1.5.2        rstudioapi_0.14 xml2_1.3.3     
[13] vctrs_0.5.1     desc_1.4.2      tools_4.2.2     stringr_1.5.0  
[17] glue_1.6.2      purrr_0.3.5     pkgload_1.3.2   xfun_0.35      
[21] compiler_4.2.2  knitr_1.41 
```

