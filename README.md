# Write your PhD thesis in Rmarkdown - University of Bergen

This is an Rmarkdown dissertation/thesis template for PhD students at University of Bergen and was created by Marius Langvad (PhD student). The template is a combination of RMarkdown and the official UiB LaTeX template (<https://avhandling.uib.no/>) to achieve proper formatting (no LaTeX skills required).

To install this template, copy these commands to your R console in RStudio:

```
if (!require("remotes")) 
  install.packages("remotes", repos = "https://cran.rstudio.org")
remotes::install_github("rstudio/bookdown")
remotes::install_github("SaltyRydM/bergendown")
```

Once installed you can open a fresh template by clicking:

- File -> New File -> R Markdown... -> From Template -> UiB dissertation template

All the `*.Rmd` files correspond to the different sections of the dissertation. PS: Even though the title page is written in LaTeX (and might look frighting), you only need to replace the text that is already there (e.g. "Main Title", "Subtitle", "First-name Last-name"...).

You may **render** the template at any time by knitting the mother document. The mother document should be called `untitled.Rmd` unless you have given it a specific name when opening a new template. In the mother document you can also add/remove/rename sections to fit your thesis outline. By default the knitting will generate a PDF, but you may change the mother document to render a word file by changing `bookdown::pdf_document2:` to `bookdown::word_document2:` in the YAML section. However, the front page graphics will not be included in the word document, but you can easily copy this from the official UiB word template at <https://avhandling.uib.no/>. I found it practical to render to word document when getting feedback, so that non R users may easily provide comments on the thesis.

Furthermore, the YAML section in the mother document provides proper format of the dissertation, so it can be shrunken to a smaller book-format (17 x 24 cm) before print (which means that you don't have to worry about this). Additionally, this section loads in the bibliography file containing the references written in `BibTex` format, and it loads in the `preamble.tex` file that loads in necessary LaTeX commands and packages.

Check out the file called `chX_examples.Rmd` to see some nice examples and useful commands.

If you prefer to manually download a template file you can do it by clicking [here](https://github.com/VirVar-project/UiB-dissertation-template/archive/refs/heads/main.zip). Note, this download link is no longer maintained and may be outdated.

This work is licensed under [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).

