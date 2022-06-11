# Project-Tourism

**Problem Statement**

Year on year, hotels are witnessing an increased trend with cancellations. With one out of four hotel guests canceling bookings ahead of a stay, the trend has led to hotels not being able to accurately forecast occupancy within their revenue management besides facing loss in opportunity cost (unsold room due to cancellation). Some hotels think that high cancellations is the new norm in the industry. This however is a completely wrong approach.

**Goal**

The Goals of this project is to find out the characteristic of customers who cancelled and finding a pattern in cancelled booking by doing an exploratory data analysis and to build a classification machine learning model to predict cancellation, that has accuracy score around 0.75 - 0.9.

**Dataset Description**

0   **hotel**: Resort Hotel and City Hotel

1   **is_canceled**: Value indicating if the booking was canceled (1) or not (0)

2   **lead_time**: Number of days that elapsed between the entering date of the booking into the PMS and the arrival date

3   **arrival_date_year**: Year of arrival date

4   **arrival_date_month**: Month of arrival date

5   **arrival_date_week_number**: Week number of year for arrival date

6   **arrival_date_day_of_month**: Day of arrival date

7   **stays_in_weekend_nights**: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel

8   **stays_in_week_nights**: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel

9   **adults**: Number of adults

10  **children**: Number of children

11  **babies**: Number of babies

12  **meal**: Type of meal booked. Categories are presented in standard hospitality meal packages: Undefined - SC - BB - HB - FB
                    
13  **country**: Country of origin. Categories are represented in the ISO 3155–3:2013 format

14  **market_segment**: Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”.Categories:Direct - Corporate - Online TA - Offline TA/TO - Complementary - Groups - Undefined - Aviation

15  **distribution_channel**: Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”.Categories: Direct - Corporate -TA/TO -Undefined - GDS

16  **is_repeated_guest**: Value indicating if the booking name was from a repeated guest (1) or not (0)

17  **previous_cancellations**: Number of previous bookings that were cancelled by the customer prior to the current booking

18  **previous_bookings_not_canceled**: Number of previous bookings not cancelled by the customer prior to the current booking

19  **reserved_room_type**: Code of room type reserved. Code is presented instead of designation for anonymity reasons. Different categories are 'C','A', 'D','E', 'G', 'F', 'H', 'L', 'P', 'B'

20  **assigned_room_type**: Code for the type of room assigned to the booking.Code is presented instead of designation for anonymity reasons.Different categories are C' 'A' 'D' 'E' 'G' 'F' 'I' 'B' 'H' 'P' 'L' 'K' 

21  **booking_changes**: Number of changes made to the booking from the moment the booking was entered on the PMS until the moment of check-in or out

22  **deposit_type**: Indication on if the customer made a deposit to guarantee the booking. This variable can assume three categories: No Deposit - Refundable - Non Refund 

23  **agent**: ID of the travel agency that made the booking

24  **company**: ID of the company that made the booking or responsible for paying the booking.

25  **days_in_waiting_list**: Number of days the booking was in the waiting list before it was confirmed to the customer

26  **customer_type**: Type of booking, assuming one of four categories:Transient - Transient-Party - Contract - Group

27  **adr**: Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights

28  **required_car_parking_spaces**: Number of car parking spaces required by the customer

29  **total_of_special_requests**:Number of special requests made by the customer (e.g. twin bed or high floor)

30  **reservation_status**: Reservation last status, assuming one of three categories: Canceled - Check-Out - No-Show

31  **reservation_status_date**: Date at which the last status was set. 
