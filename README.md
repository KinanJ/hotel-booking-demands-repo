# Hotel booking demands of a city and a resort hotel in Portugal
## by Kinan Jemil Hassen

## Dataset

The dataset contains 117430 hotel reservations with 25 features that give further details on the bookings. Arrival date, hotel type, total length of stay, average daily rates, and customer type are some of the main features included.

The dataset can be found [here](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand) and the description of the dataset can be found [here](https://www.sciencedirect.com/science/article/pii/S2352340918315191) .<br>

The objective of this project was to conduct an exploratory data analysis on a dataset containing booking information for a city hotel and a resort hotel. Various characteristics of the bookings such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things are included in the data. Univariate, bivariate and multivariate relationships of the variables were explored and visualized using different plotting techniques.


## Summary of Findings

The initial phase of the analysis task was to wrangle and clean the dataset. I used a custom dataset which I stated above and performed some cleaning operations like converting columns into the correct data types. I converted the date columns into their correct format whcih is the datetime datatype. I also added a new variable called 'total_stay' which is the combination of 'stays_in_weekend_nights' and 'stays_in_week_nights' variables. This new variable eased the task of calculating the total length of stay.

After the completion of the data wrangling, I proceeded to explore the univariate relationships. I found that there tended to be an increase in reservations during the summer and fall season. I also tried to explore the likelihood of guests getting assigned their requested rooms. 88% of the guests had their requests satisfied. Exploring the deposit type variable, results showed that majority of the reservations were made without any advance payment. Even though that was the case, most of the requests for room types during reservations have been satisfied. So, deposit type hasn't impacted the room allocation significantly meaning requested and assigned room types were the same in most cases. Another question I tried to answer was the most popular origin country of the guests. Portugese nationals made the most number of reservations followed by Great Britain and France.

The next phase was the bivariate exploration. I was able to find out that there was a very weak correlation between the length of stay and the average daily rates. The rates had close to no effect in the length of stay. I also found that there was a gradual increase in reservation throughout the years with a slight dip towards mid 2017. City hotel reservations made up larger share of the reservations. Regarding classification of reservations by customer type, most reservations made are by Transient customer types (when the booking is not part of a group or contract, and is not associated to other transient booking). Second most common customer is Transient party which is when the booking is transient, but is associated to at least other transient booking.

Finally, I performed some multivariate explorations. I found that the average length of stay was higher in resort hotels. Further analyzing the data using multiple vairiables, it was apparent that contract customer types stayed twice as long as compared to other customer types in resort hotels. For city hotels, Transient customers slightly stay longer than the other types. I also attempted to perform a detailed analysis on the average daily rates variable. Transient customers spent more than the other customer types in both types of the hotel while transient-party customer types spent the least amount.

## Key Insights for Presentation

- City hotels made up 66.5% of the reservations while resort hotels reservations were 33.5%.

- There was an increase in reservations in the months Septmeber and October for the years 2015 and 2016. And for the year 2017, May and June were the most popular months.

- Results showed that was a gradual increase in reservations through out the years with a slight dip towards mid 2017. Overall, there were more reservations for city hotels than resort hotels.

- Investigating demand during the month reveals that; daily demand of "Customers" tended to be more volatile compared to "Subscribers"; and that peaks and off-peak days are different for the two groups.

- Correlation between the length of stay and the average daily rates was very weak. The rates had close to no effect in the length of stay. Further analysis supported the earlier finding where there was close to zero correlation between hotel rate and length of stay in both city and resort hotels.

- It was evident that reservations made through Offline travel agents and tour operators resulted in guests staying longer. On average, these customers stayed for 6 days. Guests that made the reservations themselves stayed only half as much which was around 3 days on average.

- In resort hotels, contract customer types stayed twice as long as compared to other customer types. However, in city hotels, Transient customers slightly stayed longer than the other types.

- Exploration done to analyze proportion of the guests nationalities showed that Portugese nationals were the ones with most number of reservations followed by citizens of Great Britain and France.

## Resources
- [Hotel bookings demand dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
- [Data description](https://www.sciencedirect.com/science/article/pii/S2352340918315191)
