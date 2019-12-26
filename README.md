GeoUy 

**geouy** is an R package that allows users to easily access official spatial data sets of Uruguay. The package includes a wide range of geospatial data as *simple features*, available at various geographic scales and for various years with harmonized attributes and projection (see detailed list below).

## Installation
```R
# From CRAN
  install.packages("geouy")
  library(geobr)

# or use the development version with latest features
  utils::remove.packages('geouy')
  devtools::install_github("RichDeto/geouy")
  library(geouy)
```
obs. If you use **Linux**, you need to install a couple dependencies before installing the libraries `sf` and `geouy`. [More info here](https://github.com/r-spatial/sf#linux).



## Basic Usage

The syntax of all `geouy` functions operate one the same logic so it becomes intuitive to download any data set using a single line of code. Like this:


## Available datasets:


| Capa | Fuente | Years available | Fuente |
|-----|-----|-----|-----|
|`"Departamentos"`| `"IDE"` | 2014 | wfs |
|`"Secciones"`| `"INECenso"` | 2011 | wfs |
 


### Other functions:


| Function | Action|
|-----|-----|
|`geocode_ide_uy`| Allows geocoding directions using IDE_uy  |
| ... | ... | ... | 
