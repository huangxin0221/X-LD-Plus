# X-LD
R package {XLDPlus} has been developed to compute for complex LD patterns for biobank-scale sample.

## Installation

```r
# This is an R console
# 1. First, make sure the following R packages are installed
install.packages(c("ggplot2","zip","data.table"))
# 2. Then, download the source codes of X-LD (XLDPlus_0.1.0.tar.gz), and install it.
install.packages("XLD_0.1.0.tar.gz",type="source",repos=NULL)
```

## Usage
```r
# This is an R console
# 1. load package
library(XLDPlus)
# 2. help document 
help("X_LD_Plus")
# 3. examples
X_LD_Plus(input="test",output="test",population_type = "inbred",autosome=5,B=100)
```
