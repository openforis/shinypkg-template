# shinypkg-template

Instructions to create a structured package around a shinyapp.

### Refs:

-   <https://engineering-shiny.org/index.html>
-   <https://r-pkgs.org/>
-   <https://happygitwithr.com/>
-   <https://rstudio.github.io/bslib/>
-   <https://appsilon.github.io/shiny.i18n/articles/basics.html>
-   <https://rstudio.github.io/crosstalk/using.html>

### Shiny app package development steps:

1.  Create a Github repository to host the application's package
2.  Create a Rstudio project linked to the Github repository
3.  Create the package core files in the Rstudio project
4.  Copy/paste the function and module template files to the R project
5.  Develop the application functions (modules and analytical), going back and forth between these 4 actions:
    1.  Edit the template files to customize the application
    2.  Create / update new files / functions as necessary
    3.  Load functions to the local environment, update documentation, run checks (resp. `load_all()`, `document()` and `check()` from the `devtools` package)
    4.  Commit and push changes to the Github repository.
