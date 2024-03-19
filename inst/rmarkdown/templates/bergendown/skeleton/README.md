# Write your UiB PhD thesis in Rmarkdown

This is an RMarkdown dissertation/thesis template for PhD students at University of Bergen and was created by Marius Saltvedt (PhD student). The template is a combination of RMarkdown and the official UiB LaTeX template (<https://avhandling.uib.no/>) to achieve proper formatting (no LaTeX skills required).

You can download the template by clicking [here](https://github.com/VirVar-project/UiB-dissertation-template/archive/refs/heads/main.zip)

All the `*.Rmd` files correspond to the different sections of the dissertation. PS: Even though the title page is written in LaTeX (and might look frighting), you only need to replace the text that is already there (e.g. "Main Title", "Subtitle", "First-name Last-name"...).

You may **render** the template at any time by knitting the file `main.Rmd` to generate a PDF version of the dissertation. In this file you can also add/remove/rename sections to fit your thesis outline.

The YAML section in the `main.Rmd` provides proper format of the dissertation, so it can be shrunken to a smaller book-format (17 x 24 cm) before print (which means that you don't have to worry about this). Additionally, this section loads in the bibliography file containing the references written in `BibTex` format, and it loads in the `preamble.tex` file that loads in necessary LaTeX commands and packages.

Check out the file called `chX_examples.Rmd` to see some nice examples and useful commands.

This work is licensed under [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).
