# Hotel Bookings Data Analysis - *Readme in progress*

## Overview

I'm learning data analysis through a Discord channel that I found through Reddit. Each week will feature a different exploratory analysis project along with data cleaning, visualization practice, statistical analysis and data storytelling. Most if not all of the datasets will be from Kaggle.

In this week's project, we will analyze hotel bookings to figure out the standard pattern of booking and provide insight to help derive a marketing strategy for our imaginary marketing team. The data is from Kaggle and only has data from 2015-2017.

### Understanding the column data

* **Hotel**
    - H1: Resort hotel
    - H2: City hotel
* **is_canceled**
    - 1: Canceled 
    - 0: Not canceled
* **lead_time**
    - No of days thaat elapsed between entering date of booking into property management system and arrival date
* **arrival_date_year**
    - Year of arrival date (2015-2017)
* **arrival_date_month**
    - Month of arrival date (Jan - Dec)
* **arrival_date_week_numberr**
    - Week number of year for arrival date (1-53)
* **arrival_date_day_of_month**
    - Day of arrival date
* **stays_in_weekend_nights**
    - No of weekend nights (Sat/Sun) the guest stayed or booked to stay at the hotel
* **stays_in_week_nights**
    - No of week nights (Mon - Fri) the guest stayed or booked to stay at the hotel
* **Adults** 
* **Children**
* **Babies**
* **meal** 
    - Type of meal booked. Undefined/SC – no meal package; BB – Bed & Breakfast; HB – Half board (breakfast and one other meal – usually dinner); FB – Full board (breakfast, lunch and dinner)
* **country**
* **market_segment** (a group of people who share one or more common characteristics, lumped together for marketing purposes)
    - TA: Travel agents
    - TO: Tour operators 
* **distribution_channel** (A distribution channel is a chain of businesses or intermediaries through which a good or service passes until it reaches the final buyer or the end consumer)
    - TA: Travel agents
    - TO: Tour operators
* **is_repeated_guest** (value indicating if the booking name was from repeated guest)
    - 1: Yes
    - 0: No
* **previous_cancellations**
    - Number of previous bookings that were cancelled by the customer prior to the current booking
* **previous_bookings_not_canceled**
    - Number of previous bookings not cancelled by the customer prior to the current booking
* **reserved_room_type**
    - Code of room type reserved. Code is presented instead of designation for anonymity reasons.
* **assigned_room_type**
    - Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation reasons (e.g. overbooking) or by customer request. Code is presented instead of designation for anonymity reasons.
* **booking_changes**
    - Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation
* **deposit_type**
    - Indication on if the customer made a deposit to guarantee the booking. This variable can assume three categories: No Deposit – no deposit was made; Non Refund – a deposit was made in the value of the total stay cost; Refundable – a deposit was made with a value under the total cost of stay.
* **agent**
    - ID of the travel agency that made the booking 
* **company**
    - ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons
* **day_in_waiting_list**
    - Number of days the booking was in the waiting list before it was confirmed to the customer
* **customer_type**
    - Contract - when the booking has an allotment or other type of contract associated to it; 
    - Group – when the booking is associated to a group; 
    - Transient – when the booking is not part of a group or contract, and is not associated to other transient booking; 
    - Transient-party – when the booking is transient, but is associated to at least other transient booking
* **adr (average daily rate)**
    - average daily rate = $ \frac{Sum Of All Lodging Transaction}{Total Number Of Staying Night}$
* **required_car_parking_spaces**
    - Number of car parking spaces required by the customer 
* **total_of_special_requests**
    - Number of special requests made by the customer (e.g. twin bed or high floor)
* **reservation_status**
    - Canceled – booking was canceled by the customer; 
    - Check-Out – customer has checked in but already departed; 
    - No-Show – customer did not check-in and did inform the hotel of the reason why
* **reservation_status_date**
    - Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel

## GitHub Link
[Hotel Bookings Analysis](https://github.com/dangconnie/Hotel-Bookings-data-analysis)


## Table of Contents

[Description/Overview](#overview) | [GitHub Link](#github-link) | [Table of Contents](#table-of-contents) | [Technologies](#skills-and-technologies) | [Results](#results) | [Conclusions](#conclusions)


## Skills and Technologies
The following skills and technologies were used:

   * Python
   
   * Data cleaning
   
   * Exploratory data analysis
   
   * Data visualization
   
   * Statistical analysis
   
   * Data storytelling
   
   * Kaggle
   
   * Jupyter Notebook/Google Colab
   
## Results

## Conclusions
*   City hotels are more popular throughout the year. Resort hotels, although generally much more expensive than city hotels, are more popular for families with babies. Those that travel with children or babies have no specific preference for the type of hotel. 

*   Between May and Aug are where the highest numbers of bookings are. We should target these months for advertising. It would also be interesting to see what was done differently during 2016 that caused the number of bookings to go up.

*   We have a huge number of visitors from western Europe, namely France, UK and Portugal being the highest, so focus should be here for location.

*   The majority of the distribution channels and market segments involve travel agencies (online or offline). We can target our marketing area to be on these travel agencies' website and work with them since majority of the visitors tend to reach out to them. 

*  The majority of the bookings do not require deposit. That could explain why cancellation rate was actually 50% of non-cancellation rate. If we want to up the non-cancellation rate, we might want to look at requiring deposit.

*  There is a low number of repeated guests. If we target these repeated guests by building relationships, we may see a higher number of returning guests. These guests may, in turn, provide reference to their friends and family and cause an overall increase in number of bookings.
