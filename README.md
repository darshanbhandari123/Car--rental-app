# README

Functionalities covered

Customers
Customers can login and reserve a car based on the time constraints present in the Problem Statement. The customers cannot edit the cars The Customers can book,checkout,return the cars and request for a checkedout/reserved car.

To make a reservation or directly checkout a car, customer needs to click on 'Search' button leaving the seacrh tab empty.

While checking out a car directly without previously reserving the car, the time field can be left blank. Even if any time is specified by the customer, then too the application would take the system time and simply neglect the specified time. However, while reserving a car the time must be specified.

The hint 'Enter a keyword here!' could be given any parameter from (location or model or manufacturer or style or status) to search.

The customer can make a suggestion but cannot see the status of his made suggestion.Only the admin/superadmin can see such suggestions.The customer can only suggest the manufacturer and model name, the rest of the attributes need to be specified by the admin before adding the car to the database.

A new customer will get a notification after signinh up.

Cars
A car can be added by admin/superadmin. A car can have status as available/booked/checked out states. Once the car is reserved, it will be  be visible to customers to checkout. 

Admins
Admins can view all customers and cars. They can also add a car, edit a reservation for the customer and also book a car for a particular customer. Admins can add other admins.

Superadmins
Superadmins can add admins and superadmins. They perform everything that an admin can perform.

Email:
The customer gets an email when the car becomes available.
Do provide correct email id for this feature to work.

Suggestion:
The cutsomer can suggest to include some cars by providing manufacturer and model information.
