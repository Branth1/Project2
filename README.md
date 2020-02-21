# Project2
Shared Colab Link:
https://colab.research.google.com/github/Branth1/Project2/blob/master/Project2c.ipynb

GitHub Link:
https://github.com/Branth1/Project2
## Description

This is a study of the data collected by the Bulk Meteorology Instrument Package at two different sites from the OOI database. 

The data sets being studied and compared are the wind speeds and precipitation rates for two different sites. The following analysis will look at the the data from theses sites and determine if there is any relation between the two. Can we use data from one site to predict data at the other? 

It should be noted that there may exist an error in the Coorelated analysis of the Oregon Shelf Surface Mooring Data. Although attempts have been made to verify this data, further testing would be needed to confirm or disprove the accuracy of the analysis.

## Background

**The questions we are looking to solve are as follows:**

        1-Is there any relation between the windspeed and rain rate at each site?

        2-Is there any coorelation between the wind at one and the other?

        3-Is there any coorelation between the rain at one site and the other?

        4-What patterns if any can be seen between the average rain rate at both sites?

        5-What patterns if any can be seen between the average wind speed at both sites?

**The sites and dates for recording are as follows:**

Oregon Shelf Surface Mooring

Oregon Offshore Surface Mooring

All Data Was Collected Between Jan 01, 2019 and Jan 01, 2020

For additional information on the instruments used please see the link to the code above.

## Solution/Results

The data was analyzed utilizing the code found in the link above. First the data was requested from the OOI website and the rain rate and wind speed for each site were analyzed:
**Initial Data Analysis**
Note:for the following graphs, the vertical bands have been added to further clarify trends at each site:

        Blue = No wind or Rain

        Green = Winid but No Rain

        Red = Rain and No Wind

        Yellow = Rain and Wind
        
**Oregon Shelf Surface Mooring**

Blue = No wind or Rain

Green = Wind but No Rain

Red = Rain and No Wind

Yellow = Rain and Wind

![](https://github.com/Branth1/Project2/blob/master/Oregon%20Shelf%20Data.png?raw=true)

**Oregon Offshore Surface Mooring**

![](https://github.com/Branth1/Project2/blob/master/Oregon%20Offshore%20Data.png?raw=true)

**Cross-Correlation of Wind Speed**

Note: Max Lag = -2971 @ Correlation Value = 0.0857

![](https://github.com/Branth1/Project2/blob/master/Coorelation%20Wind%20(lag-2971)(0.0857).png?raw=true)

**Cross-Correlation of Rain Rate**

Note: Max Lag = 1 @ Correlation Value = 0.4306
![](https://github.com/Branth1/Project2/blob/master/Coorelation%20Rain(0.4306)lag(1).png?raw=true)

**Monthly Average Wind Speed**

![](https://github.com/Branth1/Project2/blob/master/Average%20Wind.png?raw=true)

**Monthly Average Rain Rate**

![](https://github.com/Branth1/Project2/blob/master/Average%20Rain.png?raw=true)

## Conclusions
From the analysis conducted, the following conclusions were made:

1. 

2. 

3. 

4. 

5. 


## References

Data was downloaded from OOI:
https://oceanobservatories.org
