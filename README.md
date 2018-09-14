# US-gun-and-census-data
Exploratory analysis of FBI gun data and US census data

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
There should be no extra libraries needed to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation <a name="motivation"></a>
I was interested in using data from the FBI's National Instant Criminal Background Check System (NICS) as well as U.S. census data of state demographics to explore the following questions:

1. What states had the most gun sales and least gun sales per capita in 2016 (for handguns and long guns)? What are the census characteristics associated with these states?

2. Which states have had the largest changes in number of handgun sales and long gun sales between 2010 and 2016, according to the number of background checks completed?

3. What has been the overall trend in U.S. handgun sales and long gun sales over the years?

Estimations of gun sales in this analysis are based on the number of background checks called in. It's important to note that these data do not include private gun sales, many of which do not require a background check. However, [The Trace](https://www.thetrace.org/2015/11/black-friday-gun-sales-background-checks/) states that "the FBI’s NICS numbers are widely accepted as the best proxy for total gun sales in a given time period."

## File Descriptions <a name="files"></a>
This repository includes a jupyter notebook of the data wrangling steps, exploratory data analysis, and conclusions.

## Results <a name="results"></a>
The main findings of the code are are discussed throughout the notebook in the markdown cells and summarized in the Conclusion section of the notebook.

## Licensing, Authors, and Acknowledgements <a name="licensing"></a>
I'd like to thank Udacity for providing inspiration for the project. The NICS data and its descriptions can be found on github [here](https://github.com/BuzzFeedNews/nics-firearm-background-checks/blob/master/README.md). The U.S. Census data with information about state demographics can be found on census.gov. In addition, I will be working with another dataset collected from census.gov that lists the U.S. population per year, which can be found [here](http://www.multpl.com/united-states-population/table).
