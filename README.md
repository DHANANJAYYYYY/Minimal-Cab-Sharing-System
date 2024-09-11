# Minimal-Cab-Sharing-System
Developing a  mobile-adaptive web-based cab sharing system with Java (Spring Boot) backend, featuring user sign-up, trip posting, cab search, booking, and OTP-based verification. 
Further implemented filters for destination and time, with provisions for trip hosts and riders to interact.

Specifications:
It should have a mobile adaptive web interface.
It should have a sign up page where one can enter a DP, name, student/staff/cab-driver and phone number [for now OTP verification of phone number is not required as it is mostly a paid service, if some free service is found you are free to use it]. Please do not keep any more information about users.
It should have a tab to post a cab trip with price options for number of users, the destination and time of departure with estimated time of arrival. The one who posts can be named as "trip host" (can be a cab driver or a normal user,  just name and phone number needs to be shown)
It should have a tab to search for cabs with a destination and departure/arrival time filter. The user in search mode can be called "rider". If cab is found it should redirect to a page where one can book seats and price will be automatically shown from the options. They also should enter a pick up point (map can be incorporated or a list of common pick up points would also do). On booking the host would see the users who booked a trip and there should be provision to send a OTP to them, which can be used for cross verification at picked up.
