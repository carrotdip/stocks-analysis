# 2017-2018 Stocks Analysis
## Overview
The purpose of this analysis was to analyze the annual return for 12 different stocks to allow Steve to create informed decisions on choosing which ones to invest in. To do this, the total daily volume as well as the starting and ending values were determined. Subsequently, the annual return was calculated. To make it visually appealing and easier to distinguish, the return cells were set to the color red for negative returns and green for positive returns. With this analysis, Steve can make versed decisions on which particular stocks to invest in.
## Results
The total daily volume was calculated by using a nested for loop to add up all the daily volumes for each unique ticker. 
![txt](https://github.com/carrotdip/stocks-analysis/blob/76313c8a55ab0a6327622c131567ad67bb117d77/Screen%20Shot%202021-11-13%20at%202.51.45%20PM.png)\
The starting and ending prices were then determined by using a conditional/decisional statement to find the closing cost of each ticker at the beginning of the year and at the end of the year. 
![txt](https://github.com/carrotdip/stocks-analysis/blob/d8ca65df86a7ffeefd2d5193faa399ebabd88370/Screen%20Shot%202021-11-13%20at%202.54.27%20PM.png)\
These values were then outputted onto a new spreadsheet within the Excel file. A calculation was used with the starting and ending prices to determine the annual return of that year.
![txt](https://github.com/carrotdip/stocks-analysis/blob/92cdc0efd8301534eb35cfe7c3722c7ba251e0b3/Screen%20Shot%202021-11-13%20at%202.55.27%20PM.png)\
The code was then refactored to be able to perform the analysis on two different sheets based on the year. An Analysis and Clear button were also added for ease. Steve was interested in the run times for each of these analyses so a timer was incorporated into the VBA macro. 
![](https://github.com/carrotdip/stocks-analysis/blob/5844f67a7a81657e703937de259b1068e8634284/Screen%20Shot%202021-11-13%20at%203.00.34%20PM.png)\
![](https://github.com/carrotdip/stocks-analysis/blob/5844f67a7a81657e703937de259b1068e8634284/Screen%20Shot%202021-11-13%20at%203.00.42%20PM.png)
The outputs for the timer is as follows:\
![2017](https://github.com/carrotdip/stocks-analysis/blob/9a2e7ee3ad34c4e1d5f7b8f6e415b328f4a52c2c/Resources/VBA_Challenge_2017.png)\
![2018](https://github.com/carrotdip/stocks-analysis/blob/9a2e7ee3ad34c4e1d5f7b8f6e415b328f4a52c2c/Resources/VBA_Challenge_2018.png)\
The results of the 12 stocks analyses produced the following results:\
![txt](https://github.com/carrotdip/stocks-analysis/blob/c3a7646eb673f2e978f25421318433b4aedafd54/All%20Stocks%20(2017).png)\
![txt](https://github.com/carrotdip/stocks-analysis/blob/c3a7646eb673f2e978f25421318433b4aedafd54/All%20Stocks%20(2018).png)

## Summary
Refractoring code is beneficial to clean up and simplify code. Simplifying the code will allow for easier navigation and interpretation, and make debugging (in the future) much more efficient. Refactoring, however, does take more time and effort for the same outcome, but it will be more beneficial in the long run. The advantages of refactoring in this analysis specifically allowed for the same analysis but with a shorter script. The way I refactored the code allowed for one loop to run, rather than a nested loop. This will save on time and resources when analyzing larger amounts of data. It will also be easier to incoporate new data sets for years to come. 
