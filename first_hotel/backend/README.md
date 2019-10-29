## You have come at the perfect time to be the first developer to help Expedia sell its first hotel room!

Yes, this brand new hotel comes equipped with just one room, and the best part for our customers, it's absolutely free!

So needless to say, we are expecting alot of business, and we'll need a way to reserve this beautiful new room.

Here are the current high level requirements for our new reservation system:

* the room's cost is $0 per night.
* The room can be reserved for a maximum of 3 days per reservation.
* The room can be reserved with a minimum of 1 day(s) ahead of arrival and up to 1 month in advance.
* Reservations can be cancelled at anytime.
* Assume the check-in & check-out time is 12:00 AM

### Must Haves
* Add your documentation in a markdown file with any important details we should know about, like for example, how to start the application.
* Please use spring-boot when coding up your solution.
* We need your feedback here on what you thought of our challenge, don't be shy. It is always our goal to better by using data and feedback.


### System Requirements

* The users will need to find out when the room is available. So the system should expose an API to provide information of 
room availability for a given date range with a default of 1 month.

* Provide an end point for reserving the room. The user will provide his/her email & full name at the time of reservation along with the intended arrival date and departure date. Return a unique booking identifier back to the caller if the reservation is successful.

* The unique booking identifier can be used to modify or cancel the reservation later on.
 
* Provide an appropriate end point(s) to allow modification/cancellation of an existing reservation.

* Provide appropriate error messages to the caller to indicate the error use cases.

* There are no restrictions on how reservations are stored as long as system constraints are not violated.
 
* Due to the popularity of the hotel and its low cost of 0, expect very high traffic on the API since clever people will probably scripts calls, etc. The design should be easily scalable when deployed to a production environment.
 
 
### Bonus requirement
* Due to the popularity of the hotel, customers booking overlapping dates will be a concern when attempting to reserve this room. Demonstrate with appropriate test cases that the system can gracefully handle concurrent requests to reserve the room.


### Notes
* We love to see clean code bases that are easy to read. We favor readable code vs over-commenting (only comment when necessary)
* API documentation is great, swagger is even better (optional)
* We hope you have fun with it!
