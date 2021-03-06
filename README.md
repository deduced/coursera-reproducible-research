## Coursera Reproducible Research Repository

This course is part of the Data Science Specialization at Coursera.org. 

The link to the course is [here](https://www.coursera.org/learn/reproducible-research/home/welcome)



## Overview

Storms and other severe weather events can cause both public health and economic problems for communities and municipalities. Many severe events can result in fatalities, injuries, and property damage, and preventing such outcomes to the extent possible is a key concern.

This project involves exploring the U.S. National Oceanic and Atmospheric Administration's (NOAA) storm database. This database tracks characteristics of major storms and weather events in the United States, including when and where they occur, as well as estimates of any fatalities, injuries, and property damage.



There is also some documentation of the database available. Here you will find how some of the variables are constructed/defined.



The Storm Data database is uploaded to this repository with the filename `repdata%2Fdata%2FStormData.csv.bz2`. 



Additional documentation of the Storm Data database is below, including how some of the variables are constructed: 

- National Weather Service [Storm Data Documentation](https://d396qusza40orc.cloudfront.net/repdata%2Fpeer2_doc%2Fpd01016005curr.pdf)
- National Climatic Data Center Storm Events [FAQ](https://d396qusza40orc.cloudfront.net/repdata%2Fpeer2_doc%2FNCDC%20Storm%20Events-FAQ%20Page.pdf)



Note that the events in the database start in the year 1950 and end in November 2011. In the earlier years of the database there are generally fewer events recorded, most likely due to a lack of good records. More recent years should be considered more complete.



## Project Overview

The basic goal of this project is to explore the NOAA Storm Database and answer some basic questions about severe weather events. We will use the database to answer the questions below and show the code for the entire analysis using reproducible research techniques, specifically RMarkdown and Knitr. The analysis will also be published to [RPubs](https://rpubs.com).



The data analysis will answer the following questions: 

1. Across the United States, which types of events (as indicated in the `𝙴𝚅𝚃𝚈𝙿𝙴` variable) are most harmful with respect to population health?
2. Across the United States, which types of events have the greatest economic consequences?



The analysis will be written as if it were to be read by a government or municipal manager who might be responsible for preparing for severe weather events and will need to prioritize resources for different types of events. However, no specific recommendations will be made in the outputted report. 