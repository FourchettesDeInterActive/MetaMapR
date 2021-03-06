![](https://raw.githubusercontent.com/dgrapov/MetaMapR/gh-pages/images/white_logo.jpg)

[MetaMapR](http://dgrapov.github.io/MetaMapR/) 
========
## A metabolomic network mapping tool 
![demo](Manual/metamapr_long.gif)

### Installation
Requires [R](http://cran.us.r-project.org/) and [Shiny](https://github.com/rstudio/shiny-server). 
Try it out using the [Shiny glimmer server](http://spark.rstudio.com/dgrapov/MetaMapR/) 
or run locally by pasting the following code into the R console:
```r
library(shiny)
shiny::runGitHub('MetaMapR','dgrapov')
```
Alternatively download the .zip file, unzip and run the following code (example for file on desktop)
```r
library(shiny)
shiny::runApp('~/../Desktop/MetaMapR-master/MetaMapR-master')
```
NOTE: modify file paths for OSX and LINUX 

### Instructions
* [Tutorial](http://ufpr.dl.sourceforge.net/project/metamapr/Metmapr%20v1.2.1%20tutorial%20v1.doc.pdf) (a more detailed version coming soon)
* [Examples](http://dgrapov.github.io/MetaMapR/)

### Information
Version: MetaMapR version 1.3.1 (11/19/14)

News: [See the newest features.](https://github.com/dgrapov/MetaMapR/blob/master/NEWS.md)

License: GNU General Public License (v3), [read more](https://github.com/dgrapov/MetaMapR/blob/master/LICENSE)

### Citation
If you find MetaMapR useful please cite this tool using the doi listed below.

Dmitry Grapov (2014) MetaMapR: Metabolomic Network Analysis and Visualization Tool

[![DOI](https://zenodo.org/badge/7400/dgrapov/MetaMapR.png)](http://dx.doi.org/10.5281/zenodo.12880)

### TODO
* add partial correlations
* add cytoscape.js networks
* enable network mapping


