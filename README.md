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

**Oregon Shelf Surface Mooring**

**Blue = No wind or Rain
Green = Wind but No Rain
Red = Rain and No Wind
Yellow = Rain and Wind**

![](https://github.com/Branth1/Project2/blob/master/Oregon%20Shelf%20Data.png?raw=true)

**Summer**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/dfs1time.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/dfs1ssp.png)

**Coastal Endurance › Oregon Offshore Cabled Shallow Profiler Mooring**

**Winter**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df2time.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df2ssp.png)

**Summer**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df2stime.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df2sssp.png)

**Coastal Endurance › Oregon Offshore Cabled Deep Profiler Mooring**

**Winter**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df3time.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df3ssp.png)

**Summer**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df3stime.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df3sssp.png)

**Cabled Array ›Oregon Slope Base Shallow Profiler**

**Winter**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df4time.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df4ssp.png)

**Summer**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df4stime.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df4sssp.png)

**Cabled Array ›Oregon Slope Base Deep Profiler**

**Winter**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df5time.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df5ssp.png)

**Summer**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df5stime.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df5sssp.png)

**Cabled Array ›Axial Base ShallowProfiler**

**Winter**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df6time.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df6ssp.png)

**Summer**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df6stime.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df6sssp.png)

**Cabled Array ›Axial Base Deep Profiler**

**Winter**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df7time.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Winter/df7ssp.png)

**Summer**

![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df7stime.png)
![](https://raw.githubusercontent.com/Branth1/CTD-Project1/Summer/df7sssp.png)

## Conclusions
From the analysis conducted, the following conclusions were made:

1. Comparing the # of dives per day for the shallow profiler in winter it has about 2 if we count the half dive and summer it has 4. For the deep profiler it has 12 in winter and about 2 in summer. It is important to note that some of the data sets may not have collected during the entire 24 hour period. In addition, the deep profiler data in winter does not encompass an entire dive as seen by the small range of the y-axis.
2. In the summer we find the maximum average SSP at Cabled Array \&gt; Oregon Slope Base Deep Profiler. In the winter the max average SSP is found to be at the Coastal Endurance \&gt; Oregon Shelf Surface Piercing Profiler Mooring. The deep profiler in summer is as expected, having some of the deepest waters on that dive and warmer temperatures would correlate to a maximum SSP. However, the surface profiler found in winter is unexpected. We would assume that at the surface there would be a slower SSP than at very deep waters. 
3. When comparing the SSP profile for day and night, this is slightly tricky to do since we have to account for the dives in this analysis. The SSP experiences much greater variations from the changing depth than it does from the time of day. However, if we look at the same depth at night and day, a slight variance is noticed. 
4. Looking at the SSP profile for all profilers and comparing between winter and summer it would be expected that the profiles would have greater values in the summer due to the increased temperatures. This can be seen by the steeper slope visible in the winter graphs.
5. It was attempted to find the average SSP profiles recorded at the same day in summer and winter for all profilers. However, some profilers only recorded during certain days, years, hours, etc. Due to this, the data was selected as closely as possible to the same day of month and the year may vary. Even with this variation, the average SSP for all profilers fit within a relatively small range of 1480-1491. The Oregon slope shallow and Oregon shelf surface profilers appear to have the highest SSP values independent of season.

## References

Data was downloaded from OOI:
https://oceanobservatories.org
