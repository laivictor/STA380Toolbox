## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

    summary(cars)

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](STA380histogram_files/figure-markdown_strict/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.

    #https://www.econometrics-with-r.org/2-1-random-variables-and-probability-distributions.html
    curve(dnorm(x),
          xlim = c(-3.5, 3.5),
          ylab = "Density", 
          main = "Standard Normal Density Function") 

![](STA380histogram_files/figure-markdown_strict/unnamed-chunk-1-1.png)

    #https://www.math.csi.cuny.edu/Statistics/R/simpleR/stat007.html
    x=rnorm(100)
    hist(x,probability=TRUE,col=gray(.9),main="normal mu=0,sigma=1")
    curve(dnorm(x),add=T)

![](STA380histogram_files/figure-markdown_strict/unnamed-chunk-2-1.png)
