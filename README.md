# Surfs Up Challenge
### Unit 9 - Bryan K

In this project, a surfing company is exploring different weather conditions and when and where may be a good place to add a surfing stand for clients to come and surf.  As a result, one has information from weather stations around the area regarding precipitation (rain fall), temparatures observed, and well as information about the weather station itself.

## Overview of the Analysis
A detailed statistical analysis will be a helpful technique to truly understand the data and what is going on with the information.  In this case, there are two key months suggested for understanding the business:  June and December.  Each of the months require similar statistical treatment for a better understanding.  From a statistical perspective the information is very straightforward:  Mean, STD, and each quad.

## Results
Provide a bulleted list with three major points from the two analysis deliverables. 
- Extra detail was added in this analysis using filter(extract('month', Measurement.date)==x).  This allows for understanding of EVERY year's month as opposed to simply the LAST year's month.
- The mean temperature in either month is not significantly different: 75 vs. 71 °F <-- WHY??  This unit makes THIS scientist CRAZY!!
- What CAN be useful is looking at the minimum temperature showing 64 in June and 56 in December.  THAT can pull a little more weight in this situation.

![image](https://user-images.githubusercontent.com/19878877/155897691-6b68fa93-2d31-425c-85b8-10e1596cc9f6.png)

![image](https://user-images.githubusercontent.com/19878877/155897730-f76188f2-93e5-4ea0-a1ca-c0df9d871308.png)

## Summary
The information provided in the simple "describe" function can be quite helpful.  Namely, there is an overall temperature range of 56° – 84° A frequency of occurances of monthly max and min should also be achievable with numpy through binning and statistics.  This too is good to understand.  
There are extra data points that could be very useful for a thorough analysis here.  Namely, when are the major storms in this area?  The weather stations are excellently equipped for this and will make a large difference for the safety of the clients.  I would also say that from a business perspective, the rainier the season, the less profit a business will pull in.  Tide measurements are also a strong plus in this area.
