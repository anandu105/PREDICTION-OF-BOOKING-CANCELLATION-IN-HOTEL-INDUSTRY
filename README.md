# PREDICTION-OF-BOOKING-CANCELLATION-IN-HOTEL-INDUSTRY


This data article describes two datasets with hotel demand data.
One of the hotels (H1) is a resort hotel and the other is a city hotel (H2).
Both datasets share the same structure, with 31 variables describing the 40,060 observations of H1 and 79,330 observations of H2. 
Each observation represents a hotel booking.
Both datasets comprehend bookings due to arrive between the 1st of July of 2015 and the 31st of August 2017, including bookings that effectively arrived and bookings that were cancelled.
Since this is hotel real data, all data elements pertaining hotel or costumer identification were deleted. 
Instead of directly extracting variables from the bookings database table, when available, the variables’ values were extracted from the bookings change log, with a timestamp relative to the day prior to arrival date. 
Not all variables in these datasets come from the bookings or change log database tables. 
Some come from other tables, and some are engineered from different variables from different tables

# Business Probelm

Hotel cancellations have been rising in the past few years due to the presence of online websites (OTA)
OTA´s are encouraging customers to cancel by providing services like book now and cancel later, free of charge, whenever you want. This results in customers booking more than one hotel and making a final decision for their stay later on, hence resulting in cancellations. Examples of the impact of cancellations on a hotel:
• Loss of revenue when they cannot resell the room.
• Additional costs of distribution channels by increasing commissions or paying for publicity to help sell these rooms.
• Lowering prices last minute, so they can resell a room, resulting in reducing profit margin.
So, what can hotels do to reduce this uncertainty and maximize their product and revenue? A lot can be done with revenue management techniques when it comes to
rates restrictions, like increasing the number of days until the customer can cancel
their booking free of cost, hence giving you more time to resell the room. But now due
to the presence of competition, we need to monitor these policies so that we don’t
loss customers due to stricter cancellation policies compared to our competitors
Therefore, it would seem that we have a complex problem and not a viable solution.
However, now we can use data science and machine learning techniques, to accurately predict which individual and specific reservations are going to cancelled.

# Requirements
The following softwares/packages are required for running the scripts:

Python 3.6.1

Scikit-learn 0.19.0
