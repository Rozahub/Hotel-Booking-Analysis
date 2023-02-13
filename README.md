# Hotel-Booking-Analysis
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.

We will perform exploratory data analysis with the help of python and other tools to get insights from the data.

Here we have tried to answer the following questions:-
1.	How Many Booking Were Cancelled?
2.	What is the booking ratio between Resort Hotel and City Hotel?
3.	What is the percentage of booking for each year?
4.	Which is the most busy month for hotel?
5.	From which country most guest come?
6.	How Long People Stay in the hotel?
7.	Which was the most booked accommodation type (Single, Couple, Family)?


Here we will perform the following operations:
•	Feature Engineering to make new features
•	Data Selection to select only relevant features
•	Transform the Data (Categorial to Numerical)
•	Split the data (Train Test Split)
•	Model the data (Fit the Data)
•	And finally Evaluate our model


Tools and libraries we have used is Python 3 and to its following packages, pandas matplotlib, seaborn, etc.:

Files
This repository contains two files other than readme file
Hotel Booking.ipynb: Google Colaboratory  Notebook file contains all the python code, documentation and visualization
hotel_bookings.csv: Our dataset file


Dataset contains following features:
1.	hotel
2.	is_canceled
3.	lead_time
4.	arrival_date_year
5.	arrival_date_month
6.	arrival_date_week_number
7.	arrival_date_day_of_month
8.	stays_in_weekend_nights
9.	stays_in_week_nights
10.	adults
11.	children
12.	babies
13.	meal
14.	country
15.	market_segment
16.	distribution_channel
17.	is_repeated_guest
18.	previous_cancellations
19.	previous_bookings_not_canceled
20.	reserved_room_type
21.	assigned_room_type
22.	booking_changes
23.	deposit_type
24.	agent
25.	company
26.	days_in_waiting_list
27.	customer_type
28.	adr
29.	required_car_parking_spaces
30.	total_of_special_requests
31.	reservation_status
32.	reservation_status_date



Result

We learned that

1.	City hotels are the most preferred hotel type by the guests and we can say City hotel is the busiest hotel. Hence, City hotel seems to be making more revenue.
2.	We get to know that 98.7% of the guests prefer "No deposit" type of deposit
3.	Only 3.9% people revisit the hotels. Rest 96.1 % were new guests. Therefore, retention rate is low.
4.	We can say the peak months are : August, July, May(Summer Time).
5.	Most of the customers (91.6%) do not require car parking spaces.
6.	Most of the bookings were made through TA/TO (travel agents/Tour operators).
7.	People generally prefer long stays on weekdays rather than weekends.
8.	We see that majority of the rooms booked are couple rooms
9.	Majority of the customers prefer online booking rather than offline booking.
10.	Average ADR for city hotel is high as compared to resort hotels. These City hotels are generating more revenue than the resort hotels.
11.	Booking cancellation rate is high for City hotels which almost 45%.
12.	Average lead time for resort hotel is high.
13.	Waiting time period for City hotel is high as compared to resort hotels. That means city hotels are much busier than Resort hotels.
14.	Resort hotels have the most repeated guests.
15.	Best stay in both the type hotel is less than 7 days.
16.	Majority of the customers has got the room type they have booked.
17.	City Hotel has the highest booking cancellation percentage.

