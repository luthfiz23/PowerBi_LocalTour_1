# PowerBi_LocalTour_1
Practicing data visualization with Power BI using a free data from kaggle. This time I'm using a local themed data, tourism data in Java, Indonesia from a dummy tourism application. I've uploaded dataset in this repository but please refer [here](https://www.kaggle.com/datasets/aprabowo/indonesia-tourism-destination) for the original source. 

## Method
The data is relatively clean, so it was already very easy to use. But I did some adjustments so i can visualize the data in a way that is informative. For example, the **user** table had a **Location** column which contains the city and the province of the users. The data would be too *noisy* and if we categorize the user in that way, so i chose to extract the province name.

## Dashboard
<img width="732" alt="image" src="https://github.com/luthfiz23/PowerBi_LocalTour_1/assets/159741452/f03adbbd-b1ea-4618-ba3a-615159f2c2c7">

## Insights
1. With 300 users, the average age is 28.7 years old. Most of the users are based in West Java (116 users).
2. There are 437 tourism spots documented in this data, spread across 5 cities: Jogjakarta, Bandung, Jakarta, Semarang, and Surabaya. Jogjakarta and Bandung have the most tourism spots with 126 and 124 destinations respectively.
3. Users rated the spots they visited and the average rating for all tourist destinations is 4.44, with a standard deviation of 0.21. This indicates that there are no existing wide gap between ratings of each spots.
4.  The average price to pay to enter the spots (excluding shopping centres, because it depends on the shopper's budget) is a little over 35K IDR. However, theme parks on their own have a higher average of 52k IDR.
5.  Jakarta have a higher average price for its tourist destinations at 72K IDR, whereas other cities average lower than 35K IDR (almost half of Jakarta's!). 
6.  Interestingly, out of 17 religious sites only one of them charges a ticket of 10K IDR and the rest are free. Religious sites also have the highest average rating of 4.71. This might be correlated to them being free to enter and because Indonesian's are pretty [religious](https://www.indonesia-investments.com/culture/religion/item69) people!
7.  The lowest rating is held by wisata bahari spots (water related activities like sailing, surfing, etc.) with a rating of 4.36. 34 out of 47 bahari spots documented in this data is located in Jogjakarta, a coastal city in the middle of Java.
8.  On average, people spend 82 minutes in tourist spots. However, a standard deviation of 36 (minutes) indicates that there are people with quite a different behavior when visitin famous places, those who spend a lot of time and those who move away quickly.
9.  There's no clear evidence of correlation between price and rating as shown in this scatterplot. <img width="302" alt="image" src="https://github.com/luthfiz23/PowerBi_LocalTour_1/assets/159741452/3c998613-f4f5-477c-a9f7-384cbdec2e5a">
10.  There's also no evidence of correlation between time spent in a spot and rating. <img width="292" alt="image" src="https://github.com/luthfiz23/PowerBi_LocalTour_1/assets/159741452/f546820e-8d97-4dec-8854-bd51f218dee9">
