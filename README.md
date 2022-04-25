# surfs_up
## Purpose
The purpose of this project is to show Advance Data Storage and Retrieval using SQLite and SQLalchemy.

## Overview
We are going to get a weather analysis of Oahu, Hawaii, to determine if a Surf and Ice-cream shop can work throughout the year. Our Data source is hawaii.sqlite.

## Results
We used SQLalchemy to retrieve SQLite database, got June and December temperatures, made a list of temperatures, created a DataFrame and got the statistics information for each month.

![Screen Shot 2022-04-24 at 7 03 35 PM](https://user-images.githubusercontent.com/43548929/165008838-65b7042f-2f7e-42f2-995e-5b461540dedf.png)
![Screen Shot 2022-04-24 at 7 04 12 PM](https://user-images.githubusercontent.com/43548929/165008884-17f2e6a5-91dd-4f57-b96f-668165109ce0.png)
* The average temperature in June is 74.94 F and in December is 71.4, so there is no a big difference between the 2 major tourist seasons, the weather seems pretty constant.
* On December the MIN. temperature can drop down to 53 F so that wont be goods news for the ice cream shop, but it seems coming from an outlier value because our first Quartile is again only 4 point below June's.
* The STD on December is higher, so the temperature measurements are more dispersed from the mean.

## Summary
* I decided to make an histogram to visualize the frequency of temperature mesaruments, so it can be easier to see how spread out they are. As we can see the on images below, the temperatures in June have a Normal distribution, meaning that most of the measures are near the mean, while the ones in December have more variation, but still most of them are between the 70 and 75 degree. 

![Screen Shot 2022-04-24 at 7 28 41 PM](https://user-images.githubusercontent.com/43548929/165010823-f2f9b48b-6bed-412a-bb39-2a696c24af7d.png)

![Screen Shot 2022-04-24 at 7 29 02 PM](https://user-images.githubusercontent.com/43548929/165010852-46d12bae-cb93-41d8-aba4-e17e43befeac.png)
* Also I got the statistics of June's precipitation and found out that precipiation is really low on June.

![Screen Shot 2022-04-24 at 7 54 04 PM](https://user-images.githubusercontent.com/43548929/165013034-41a1b295-b49f-41ce-9842-8be5985d3a69.png)
* The main concern is the rain, at it seems that the probability of raining is really low. The temperature in average are between 70 and 75, it seems good for the surfing business but I'm not sure about the ice cream, it can be kind of cold. I would suggest offering either beer or coffee to our surfing customers.
