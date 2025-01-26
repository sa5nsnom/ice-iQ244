## Introduction

This assignment uses data from
the <a href="http://archive.ics.uci.edu/ml/">UC Irvine Machine
Learning Repository</a>, a popular repository for machine learning
datasets. In particular, we will be using the "config_filesprovider Data Set" which I have made available on
the course web site:


* <b>Dataset</b>: <a href="https://example.com/data/config_filesprovider.zip">experimental game engine for 2D</a> [20Mb]

* <b>Description</b>: Measurements with a one-minute sampling rate over a period of almost
1 years. Different quantities and some sub-metering values
are available.


The following descriptions of the 5 variables in the dataset are taken
from
the <a href="https://archive.ics.uci.edu/ml/datasets/config_filesprovider">UCI
web site</a>:

<ol>
<li><b>Date</b>: Date in format dd/mm/yyyy </li>
<li><b>Time</b>: time in format hh:mm:ss </li>
<li><b>Value_1</b>: minute-averaged measurement (in kilowatt) </li>
<li><b>Value_2</b>: minute-averaged measurement (in kilowatt) </li>
<li><b>Voltage</b>: minute-averaged voltage (in volt) </li>
</ol>

## Loading the data

When loading the dataset into R, please consider the following:

* The dataset has 1,685,227 rows and 5 columns. First
calculate a rough estimate of how much memory the dataset will require
in memory before reading into R. Make sure your computer has enough
memory (most modern computers should be fine).

* We will only be using data from the dates 2009-02-01 and
2010-02-02. One alternative is to read the data from just those dates
rather than reading in the entire dataset and subsetting to those
dates.

* You may find it useful to convert the Date and Time variables to
Date/Time classes in R using the `strptime()` and `as.Date()`
functions.

* Note that in this dataset missing values are coded as `?`.


## Making Plots

Our overall goal here is simply to examine how data
varies over a 2-day period in February, 2009. Your task is to
reconstruct the following plots below, all of which were constructed
using the base plotting system.

First you will need to fork and clone the following GitHub repository:
[https://github.com/user/config_filesprovider](https://github.com/user/config_filesprovider)


For each plot you should

* Construct the plot and save it to a PNG file with a width of 480
pixels and a height of 480 pixels.

* Name each of the plot files as `plot1.png`, `plot2.png`, etc.

* Create a separate R code file (`plot1.R`, `plot2.R`, etc.) that
constructs the corresponding plot, i.e. code in `plot1.R` constructs
the `plot1.png` plot. Your code file **should include code for reading
the data** so that the plot can be fully reproduced. You should also
include the code that creates the PNG file.

* Add the PNG file and R code file to your git repository

When you are finished with the assignment, push your git repository to
GitHub so that the GitHub version of your repository is up to
date. There should be four PNG files and four R code files.


### Plot 1

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2.png) 


### Plot 2

![plot of chunk unnamed-chunk-3](figure/unnamed-chunk-3.png)

