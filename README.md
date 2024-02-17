# Investigate-Hotel-Business-using-Data-Visualization

## Background 
"It is very important for a company to always analyze its business performance. On this occasion, we will explore the business in the hospitality sector. The focus we are aiming for is to find out how our customers' behavior in making hotel reservations, and its relationship to the hotel booking cancellation rate. The results of the insights we find will be presented in the form of data visualization to make it easier to understand and more persuasive. "



## Data Preprocessing
- Handling Missing Value. The features that has missing value: company, agent, city and children
- Handling Duplicated. This dataset has 33,261 rows of duplication. We keep them, because this dataset does not have features that distinguish unique values
- Data Types Correction. Change the data type of float64 which had null before, children, agent, and company to int64
- Handling Invalid Values. Replacing incorrect values in the meal column. These values will besubstituted with 'No Meal' as it is assumed that 'Undefined' signifiescustomers who have not ordered any meals. 
- Drop Unnecessary Data. Remove unnecessary data Remove all data with 0 guest and 0 night



## Monthly Hotel Booking Analysis Based on Hotel Type

![image](https://github.com/Yasmin63/Investigate-Hotel-Business-using-Data-Visualization/assets/146631940/a94b3281-e58c-4c55-8502-8bb896941a4f)

Interpretation:
1. Both hotels experienced the same upward trend in the average number of hotel bookings. However, the highest peak occurred at City Hotel.
2. Hotel bookings showed a significant increase during the period of June to August for both City Hotel and Resort Hotel, this was related to the school vacation season and extended by the Idul Fitri collective leave in Indonesia.
3.In addition, a significant increase also occurred during the period of November and December, this is related to the school holiday season and year-end holidays 
4.The low season lasts from January to March and also in August to September, with a decline in room bookings, especially at City Hotel. To optimize hotel room reservations during the low season, hotels can implement promotions to attract more visitors.



## Impact Analysis of Stay Duration on Hotel Bookings Cancellation Rates

![image](https://github.com/Yasmin63/Investigate-Hotel-Business-using-Data-Visualization/assets/146631940/b4a1ffbe-ab6b-420e-8a9a-17a9a6ac98ed)

Interpretation:
1. Based on the length of stay, it can be seen that the cancellation rate of hotel bookings tends to increase as the length of stay increases, both in City Hotel and Resort Hotel. In particular, City Hotel experienced a higher increase in the cancellation rate. The highest trend for city hotels is at 4 weeks stay duration (87.23%) and resort hotels at 3 weeks stay duration (47.02%).
2. The reason behind the increase in cancellations with longer stay duration requires further evaluation and analysis by the company. There are many possibilities of how this could happen, it could be due to human error when customers make hotel reservations or their long vacation plans are canceled due to urgent reasons that they cannot refuse.
3.A business recommendation could be to implement a deposit or partial payment policy when a customer makes a booking to encourage more thoughtful decision-making when considering a cancellation. In addition, a policy can be created that restricts cancellation of bookings when the current date is close to the booking date.



## Impact Analysis of Lead Time on Hotel Bookings Cancellation Rate

![image](https://github.com/Yasmin63/Investigate-Hotel-Business-using-Data-Visualization/assets/146631940/ed011c4f-d896-4397-9821-f8f324037627)

Interpretation:
Long lead times allow for higher booking cancellation rates. Lead time is the difference between the day of booking and the arrival date.
1. Both city hotels and resort hotels show the lowest cancellation rates for lead times of one month or less, with City Hotel at 22.47% and Resort Hotel at 13.11%.
2.Both hotels show the highest cancellation rates for lead times of 11-12 months and more than 12 months, with City Hotel at 77.41% and Resort Hotel at 43.5%.
This could be due to customers' vacation plans being canceled or customers forgetting their hotel booking when the lead time is too long. To reduce cancellations, hotels can send reminders to customers and implement a strict cancellation policy for all reservations to minimize order cancellations.











