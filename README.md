# railway_ticket_management_system

----------------Railway Ticket Management System----------------------


-> The project is built as a part of the “Software System” Subject.


-> Download the file and extract.


-> Mainly there is server.c, client.c and client_util.h


-> All the utility functions are in client_util.h header file.


-> All the databases are in the form of C - structure and are stored in txt files.


-> Customer details (user and admin) and agent details are stored in customer.txt and agent.txt files respectively.


-> Train details and Booking details are stored in train.txt and booking.txt files respectively.


-> Compile server.c and client.c files as server and client name. (or any names. Just make sure both have different names)


-> Run server file and add admin.


-> Run client file and log in using admin(only for the first time) and add trains and users.


-> Now, we can run client files any time as required and can do the desired actions.


-> If logged in as a user, then only one active session is allowed. No multiple logins are allowed for normal users and admin. But can do multiple logins with agents.


-> Normal user and agent can -
1. View the train details
2. View his/her booking details
3. Do new bookings
4. Update and cancel the existing bookings


-> Admin can -
1. View train details
2. View user details
3. View all bookings
4. Cancel bookings and trains
5. Add users and trains
6. Add agents
