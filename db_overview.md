DB Overview
===========

Users
-----
(user_ID, first_name, last_name, car_number(optional), is_inspector(true , false), is_admin(true, false), 
 password_hash)

Parking_lots
------------
(lot_ID, name, adress, description)

Parking_places
--------------
(lot_ID, place_ID, price, description)

Payment_history
---------------
(datestamp, user_ID, cost, lot_ID, place_ID, booking_date, time_start, time_end)   
