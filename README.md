# flexdumbbell

A dynamic Dumbbell plot made with `flexdashboard`.


#### Usage

The script can be run within RStudio or using the command line (e.g. macOS Terminal application), by first executing `cd <nome directory>` to reach the directory containg the `flexdumbell.Rmd` script, then by running the command

```{bash}
% Rscript -e "rmarkdown::run('flexdumbell.Rmd', shiny_args = list(launch.browser = TRUE))"
```