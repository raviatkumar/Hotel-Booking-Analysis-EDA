# Hotel Booking Analysis EDA

https://public.tableau.com/views/ravikumarHotelBookingAnalysis/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link

![Alt text](https://github.com/raviatkumar/Hotel-Booking-Analysis-EDA/blob/main/Image/Hotel.jpg)

This dataset contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.

Using the matplotlib and seaborn libraries, EDA on Hotel Booking Analysis


## Data Description

The file contains different attributes of hotel booking details. The detailes of data is given below:

hotel: Name of hotel ( City or Resort)

is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)

lead_time: time (in days) between booking transaction and actual arrival.

id: unique identifier of each booking

no_of_babies: Number of babies

no_of_adults: Number of adults

no_of_children: Number of Children

no_of_weekend_nights: Number of weekend nights (Saturday or Sunday) the guest

stayed or booked to stay at the hotel

no_of_week_nights: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel

type_of_meal_plan: Type of meal plan booked by the customer

required_car_parking_space: Does the customer require a car parking space? (0 - No, 1- Yes)

room_type_reserved: Type of room reserved by the customer.

arrival_year: Year of arrival date

arrival_month: Month of arrival date

arrival_date: Date of the month

arrival_date_day_of_month: Day of month of arrival date

country: Country of origin of customers (as mentioned by them)

company: Id of the company making a booking

days_in_waiting_list: No. of days on waiting list.

customer_type: Type of customer(Transient, Group, etc.)

market_segment_type: Market segment designation.

repeated_guest: Is the customer a repeated guest? (0 - No, 1- Yes)

no_of_previous_cancellations: Number of previous bookings that were canceled by the customer prior to the current booking

no_of_previous_bookings_not_canceled: Number of previous bookings not canceled by the customer prior to the current booking

avg_price_per_room: Average price per day of the reservation; prices of the rooms are dynamic. (in euros)

no_of_special_requests: Total number of special requests made by the customer (e.g. high floor, view from the room, etc)

reservation_status: Whether a customer has checked out or canceled,or not showed

reservation_status_date: Reservation Status date


The dataset has 119390 rows and 32 columns.

## Analysis

The best time to book a hotel room can be major holiday when management is not working.

### When is the best time for booking a hotel?
Stays_in_week_nights:how many weeknights (Monday through Friday) the visitor stayed in the hotel?

Stays_in_weekend_nights:What is the number of weekends (Saturday or Sunday) that the visitor stays.

Arrival date month:Which month do more hotel reservations come from customers?

Arrival date year:Which year had the most bookings?

Friday, Saturday, and Sunday are often the best days to make a hotel booking.

### When is the peak seasons to hotel industry ?
Arrival date year:The months of November through March are often off-peak for hoteliers. The summer season, when attendance is at its peak, runs from June through the end of August.

### Who are the target audience who book a hotel?
No_of_babies:What is the number of infants that stayed at the hotel?

No_of_adults:What is the number of infants that stayed at the hotel?

No_of_children:What is the number of childrens that stayed at the hotel?

Babies, kids, and adults stay at this hotel during major holidays (vacations)

Customer_type:Travelers on business, tourists, attendees at small conferences, etc.

Business travellers, tour groups, small conference groups, and individual tourists,Vacationers, business travellers, employees, and event planners are some examples of the target clients.

### How hotels generate revenue?
Meal:what type of meals do people have for breakfast,lunch and dinner?

Adr:What is the hotel's average daily rate?

Days_in_waiting_list:Days on waiting list indicate how many additional reservations the hotel has received?

Is_repeated_guest:How likely is it that a consumer will return? When the client returns, he would have loved the hotel's amenities and parks.

Market_segment:what platform the customer used to make the hotel reservation. They have either been used offline, online, by an agency, etc.

## Summary and Conclusion:

People come from all over the world to stay at a hotel so that they can tour around the place that they are staying. They do not spend their day in the hotel and they only come back to sleep and shower, maybe a meal or two. City hotels are not a destination. Resorts are located in scenic areas but not near a city or anything really. People visit a resort to get away from other people and cities. They stay in the resort and probably don’t travel around as they may do when staying at a city hotel. A resort is the destination. City hotels have the majority of bookings compared to resort hotels.

Hotels saw an increase in bookings in 2016. Compared to resort hotels, the average daily charge for hotels in cities has gone up every year. Guest visit hotels every year, May to August is the busiest booking season. From November to February, the fewest reservations are made.Average daily rates in the month of August saw the most bookings at resort hotels', while the months of November and January saw the least. From June to September, there are more overnights spent overall. As the length of the stay rises, the average daily rate decreases. This suggests that for a longer stay, a better price can be negotiated for the customer. PRT(Portugal) makes the majority of reservations.

Around 77.2% of all orders are for BB (Bed & Breakfast), which is followed by HB (Half Board), SC (no meal package), Undefined, and FB (Full Board). In the market category, many individuals used internet TA/TO(TA: Travel agents,TO: Tour operators) to make hotel reservations. The aviation waiting list has the shortest wait time. There is a demand for hotel reservations as the waiting period lengthens. The majority of hotels (104641) do not require deposits, which are followed by refundable types (14587) and non-refundable types (162), with a large percentage of city hotels accepting no deposits. There are several temporary customers who have reserved recently. While 3364 guests have been repeated, 82865 guests have not. There are more one-time visitors and fewer cancellations in city hotels. several special requests in summer season.
