# Flight_Price_Prediction

## **Business Case-Study**

Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, and it will be a different story. We might have often heard travelers saying that flight ticket prices are so unpredictable. That’s why we will try to use machine learning algorithms including Linear Regression, Decision Tree, Random Forest, Gradient Boosting, and XG-Boosting to solve this problem. This can help airlines by predicting what prices they can maintain.


## **Dataset Description**

This Dataset consists Total of 10 Features and 1 Target(Price).

1) Airline: All types of airlines like Indigo, Jet Airways, Air India, and many more.

2) Date_of_Journey: The date on which the passenger journey will start.

3) Source: Name of the place from where the passenger journey will start.

4) Destination: Name of the place to which where passenger wanted to travel.

5) Route: Route through which passengers have opted to travel from the source
to their destination.

6) Dep_Time: When the passenger will depart from the source.

7) Arrival_Time: When the passenger will arrive at the destination.

8) Duration: The whole period that a flight will take to complete its
journey from source to destination.

9) Total_Stops: In how many places flights will stop.

10) Additional_Info: Information about food and other amenities.

11) Price: Price of the flight for a complete journey including all the expenses
before onboarding.

![image](https://github.com/Bamit-2021/Flight_Price_Prediction/assets/77608956/d4f6c9d0-26fc-4cb8-81c4-b0d05bb385d5)

![image](https://github.com/Bamit-2021/Flight_Price_Prediction/assets/77608956/1f482011-e7bb-4bf8-89f8-bf18ded0fdd8)


--------
## **Model Creation**

1) Linear Regression

2) Decision Tree

3) Random Forest

4) Gradient Boosting

5) XG-Boosting


## **Model Comparision Report**

![image](https://github.com/Bamit-2021/Flight_Price_Prediction/assets/77608956/fac343be-818a-4104-9961-f17dd5075d44)

![image](https://github.com/Bamit-2021/Flight_Price_Prediction/assets/77608956/29bee08b-3275-4ead-9e9e-c70225956d78)

--------
## **Challenges faced**:

We have to work in the EDA part for features like Date_of_Journey, Duration, Dep_Time, and Arrival_Time.

From Date_of_Journey we generate two columns Day and Month.

From Duration, we converted it into minutes as Duration_Mins.

From Dep_Time and Arrival_time we have to convert time-zones into Morning,
Afternoon, Evening, and Night slots accordingly.

The logic of these conversions is a little bit tricky.
