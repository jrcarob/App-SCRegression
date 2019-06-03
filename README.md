## Sobre `scregr`

[![GitHub version](https://badge.fury.io/gh/jrcarob%2FApp-SCRegression.svg)](https://badge.fury.io/gh/jrcarob%2FApp-SCRegression)


This interactive application allows you to explore how Sums of Squares are calculated in simple linear regressions. Change one of the parameters to see what happens.

Aplicación online: [scregr](https://paternogbc.shinyapps.io/SS_regression)

## Aplicación en R Studio

Antes de XXX la aplicación, instalar los siguientes paquetes:

```{r} 
install.packages(shiny)
install.packages(ggplot2)
install.packages(shinydashboard)
install.packages(grid)
install.packages(markdown)
install.packages(ggExtra)
```

To run this application localy, simple paste the following code on `R` console: 
```{r} 
 shiny::runGitHub("SSregression", "paternogbc")
```

![screenshot1](https://user-images.githubusercontent.com/45860181/58814770-a6649680-8626-11e9-8cac-a91c9b13eae6.png)


## Licencia
Software Open Source y bajo licencia pública [GPL-3.0](http://www.gnu.org/licenses/gpl-3.0.en.html)

![logo](https://raw.githubusercontent.com/paternogbc/SSregression/master/www/logo.png) 

_El logo OSI es la marca de [Open Source Initiative](http://opensource.org/)_

## Autor
José Rafael Caro Barrera | jrcarobarrera@gmail.com | [jrcarob](https://github.com/jrcarob)

## Créditos

Esta aplicación ha sido desarrollada con [shiny](http://shiny.rstudio.com/) en 
[R studio](https://www.rstudio.com/).
A partir de Gustavo Paterno 

