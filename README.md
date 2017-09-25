# readxl: the bridge to the tidyverse

### Or why I like the readxl R package

The [readxl](http://readxl.tidyverse.org/) package is part of the [tidyverse](https://www.tidyverse.org/), a set of [R](https://www.r-project.org/) packages for doing data science&mdash;helping R users get, clean, analyze and visualize data with packages that are purposely designed to work nicely together and help users develop tidy work flows.

I have become a regular user and fan of readxl, an R package that makes it easy to get data out of Excel and into R. Here are a few reasons why:

**readxl does one thing well**

It can be challenging to navigate the world of R packages&mdash;finding a package to do what you want to do with your data, or deciding which package to use, especially if there are many packages that have similar functionality. I like that readxl does one thing&mdash;import .xls and .xlsx files&mdash;and does it well. Close your eyes and imagine an Excel file with many, many sheets, or with graphs and pivot tables embedded in a sheet with raw data (*we have all seen one*)&mdash;readxl has the functions to import even *that* Excel data into R. You can specify a sheet, by name or number, or a set of cells, and you can control how R deals with blank cells in an Excel file. All you need and no more.

**readxl is a bridge for many users**

In a perfect world, in my opinion, we would blink and all raw, tabular data would be made available in flat, rectangular, machine-readable files. [Tidy data](https://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html), *sigh*. However, many students, data analysts and data producers are working in organizations and communities&mdash;the private sector, academia, governments and non-government groups&mdash;with strong ties to the Excel world.  Having easy to use and reliable tools for bridging R and Excel makes learning easier and faster for new R users. 

**readxl & Clippy**

readxl has a great logo. Hex logos and stickers are fun and kind of a thing for R packages now. I love stickers&mdash;and the [readxl logo with the paperclip Clippy's sad face](https://github.com/tidyverse/readxl/blob/master/tools/logo.png) makes me smile, everytime-I-see-it. I was a big Excel user in Clippy's time&mdash;[Clippy](https://en.wikipedia.org/wiki/Office_Assistant) was the Microsoft Office "intelligent" assistant (*cough cough*) in the late 1990's and early 2000s. While I never really understood the wide-spread animousity for poor Clippy, I also didn't even notice when the paperclip was finally pulled. I like readxl's homage to Clippy, I think the paperclip assistant deserves to be remembered.


### readxl and the tidyverse

Data import packages are sometimes easy to overlook when gushing about R packages in general&mdash;outshone by packages that help users really make data *sing*, like generating beautiful graphics using ggplot2 or turning super messy data into a tidy data frame using tidyr&mdash;both so satisfying. The readxl package, however, deserves some limelight too, in my opinion. It is an easy to use, reliable data import package for .xls and .xlsx files&mdash;creating a bridge to the tidyverse for new R users and many data users and communities with ties to the Excel world. 


You can install the readxl package with the whole tidyverse suite:

```
install.packages("tidyverse")  
```

Or just the readxl package itself:
```
install.packages("readxl")
```

You have to load the readxl package by itself. You can type `?readxl` in the console and navigate to the package index to see the set of functions available for getting that Excel file, tab or section of data into R.

```
library(readxl)
?readxl
```


 Here are a just few links and resources on readxl, the tidyverse and why take the bridge:

- [readxl documentation & vignettes](https://github.com/tidyverse/readxl)
- [tidyverse website](https://www.tidyverse.org/)
- [tidyverse packages on GitHub](https://github.com/tidyverse/tidyverse)
- [@tidyverse on Twitter](https://twitter.com/tidyverse)
- a few reasons to cross the bridge from Excel to R: [scary Excel stories curated by Jenny Bryan](https://github.com/jennybc/scary-excel-stories)


#### License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title"></span><a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>

