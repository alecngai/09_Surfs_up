# 09_Surfs_up By Alec Ngai

## Overview of the statistical analysis:

We will use SQLalchemy to do real time analysis on the data provided to determine if our clients ice cream shop business is sustainable year-round. 

## Results:

The main difference in minimum temperature in June the minimum is 64 *F but in december it drops to 56 *F which is roughly 13.5 *C, I personally believe 13*C is too cold for icecream and those days in December would be very slow. 

![June](https://github.com/alecngai/09_Surfs_up/blob/main/Resources/June_hist.png)
![Dec](https://github.com/alecngai/09_Surfs_up/blob/main/Resources/Dec_hist.png)

As we can see from the histograms the june average temperature is mainly around 70 *F to 80 *F, while December is 65 *F to 75 *F, however, this weather is still acceptable to eat icecream.

![June2](https://github.com/alecngai/09_Surfs_up/blob/main/Resources/June_Max_Avg.png)
![Dec2](https://github.com/alecngai/09_Surfs_up/blob/main/Resources/Dec_Max_Avg.png)

We now look at the difference between the Max average of each date in December and June througout the years. We can see the lowest max in December is 74 *F, and for June its 77 *F both of which still mean its a good ideal temperature to eat ice Cream. We can see the max trend for december is declining through December, while June max is steadily increasing. 

## Summary:

I preformed two additional queries to get the histogram distribution of the temperature counts just to see what the distrubution of temperatures will look like. This will give us an idea of the average temperature of the month and how the majority of the days will be like. 

My second query was to take the max temp and group by date, then take the average of that and remove the year so we can see on a per day basis of that month what the max average will look like. We could also look at the minumum values however, we want to see if it is viable therefore we focused on the max, from the data we can see it is viable to open a ice cream shop year round. 