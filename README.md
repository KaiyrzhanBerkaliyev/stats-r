Statistical Methods in R

Hand-written R implementations of the core techniques 
from a Statistical Methods course. Most functions are 
built from first principles (moments, sums, loops) instead of R's 
built-ins, so the code mirrors the formulas used in class and can
be checked step by step.

Contents
File	Topic
R/firstChapter.R ->	 raw data, frequency tables, grouped (interval) data
R/SecondChapter.R ->	contingency tables, covariance, correlation, linear regression
R/ThirdChapter.R	 ->  ts objects, autocorrelation, moving averages

Getting started

Clone the repository and, from its root folder, load the files you need in R:

source("R/firstChapter.R")
source("R/SecondChapter.R")
source("R/ThirdChapter.R")

No external packages are required. Only base R and stats are used.