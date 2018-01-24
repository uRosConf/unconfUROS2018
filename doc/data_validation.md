
## A Shiny app for data validation and rule management


The R package [validate](https://CRAN.R-project.org/package=validate) provides
an infrastructure for defining, reading, writing, and applying edit rules (data validation
rules) of any kind to statistical data. The [validatetools](https://CRAN.R-project.org/package=validate) package allows for finding redundancies and inconsistencies in certain
rule sets.

Both packages offer scripting tools to perform these tasks. For end users it would be beneficial to have an intuitive user interface to these packages extensive functionality. In the current proposal we would like to develop a *shiny* app that allows users to:

- Basic data validation:
    - Enter rules, and their metadata (descriptions).
    - Apply rules to a dataset interactively. Update as rules are added
    - Import and export rules from and to file
    - Show an interactive dashboard with results.
- Analyze rule sets:
    - Visualize the rules and the variables that they `touch'
    - Interactively look for redundancies or inconsistencies and present it to the user 
- ...


## Do you want to know more?

- Introductory [vignette](https://CRAN.R-project.org/package=validate) for `validate`
- Introductory [vignette](https://cran.r-project.org/web/packages/validatetools/index.html) for `validatetools`

Data validation in the ESS:

- Methodology of data validation [handbook](https://ec.europa.eu/eurostat/cros/system/files/methodology_for_data_validation_v1.0_rev-2016-06_final.pdf)



## Would you like to participate?

Please contact us via `uRos2018 at cbs dot nl`, with the subject `unconf`.

----
[[back to main page](../README.md)]
