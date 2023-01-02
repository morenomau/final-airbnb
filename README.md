# Final project codebook 

--------

---------

The data found in file `listings.csv` come from (http://insideairbnb.com/get-the-data). The filtered variables in the data are as follows:


| variable | type | description |
|----------|------|-------------|
| host | integer | brief description|
| id	| integer	|	Airbnb's unique identifier for the listing |
| host_response_time	| factor | How long it takes for host to respond to guests.|		
| host_response_rate	| numeric	|How often host responds to guests.	|
| host_acceptance_rate	|	numeric |	That rate at which a host accepts booking requests. |
| host_is_superhost | boolean [t=true; f=false] |	If host is a superhost|	
| host_total_listings_count	| text	|	The number of listings the host has (per Airbnb calculations) |
| host_has_profile_pic | boolean [t=true; f=false]	| If host has a profile picture	|
| latitude |	numeric		| Uses the World Geodetic System (WGS84) projection for latitude and longitude. |
| longitude	| numeric		| Uses the World Geodetic System (WGS84) projection for latitude and longitude. |
|room_type	| text	|	"[Entire home/apt|Private room|Shared room|Hotel] |
| accommodates	| integer	|	The maximum capacity of the listing |
| bedrooms	| integer	|	The number of bedrooms |
| beds	| integer	|	The number of bed(s) |
| price	| currency	|	daily price in local currency |
| minimum_nights_avg_ntm	| numeric	|	the average minimum_night value from the calender (looking 365 nights in the future) |
| maximum_nights_avg_ntm	| numeric	|	the average maximum_night value from the calender (looking 365 nights in the future) |
| number_of_reviews	| integer	|	The number of reviews the listing has |
| number_of_reviews_l30d	| integer	|	The number of reviews the listing has (in the last 30 days) |
| instant_bookable |	boolean		[t=true; f=false] | Whether the guest can automatically book the listing without the host requiring to accept their booking request. An indicator of a commercial listing. |
