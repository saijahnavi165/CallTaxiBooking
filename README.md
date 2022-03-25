# CallTaxiBooking
Created using Java in VisualCode Editor
Every line of code explained accordingly in the code.

A call taxi operator has a fleet of "n" cars. For simplicity take the count as 5 but the program
should work for any number of Taxis. (Let their names be identified as Taxi-1, Taxi-2 ....
Taxi-n)
● There are only 5 points in the city for pick-up / drop. Let the points be named A, B, C,
D&E
● All the points are in a straight line & the distance between the points are
same say 15kms
● Time taken for travel will be 15 minutes between each point.
● Charges for each travel will be calculated as Rs 50 for the first 5 kms and
then Rs 10 for subsequent kms of travel.
● During Booking, the following information is given : The Starting point, Destination
point & Start time. After dropping customer, the taxi waits there for next customer
allotment. Each customer is identified uniquely by a Cust-ID
● Write a program that does the following : During Booking, find out the taxi which will
be free at the specified time & which will be nearest to his location and allot it.
Assume all Taxis are at Point A initially.
Wait for next set of Inputs once a taxi is allotted
● Allotment Criteria :
1. Taxis available on the same location given preference first
2. If more than one taxi present on the same location, preference given to the taxi which
3. earned least during the day
