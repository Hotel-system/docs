# High lvl expectations

### Rooms

Should be definition of room which can have:
* number
* min person limit
* max person limit
* floor
* position (east side, west side etc)

### Reservation
Can be done for multiple rooms, but also can be done for single person in room. Second case example:

Three different persons which knows each other but they are not family rent single 3 person room. 
But finally they want to pay everyone for each other. There were cases in which they were communicated this
when they leave hotel sa there should be possibility to split reservation after creation.

Reservation should have:
* start date as a date
* end date as a date
* some client data

Rooms in relation with reservation can have some additional payments such us something to drink / eat in restaurant, massage in spa etc.

### Clients
All client data needed by hotel such as:
* name
* surname
* address
* ID number ?

### Payments

Payment is created when client pays for reservation. It can be done via:
* cash
* credit card

### Safe operations

- Cash deposit. Done once per day when employees from restaurant and spa brings up some cash from their all day activity.
- Cash withdraw. Done when boss wants money to be withdrawn, or there is a need to pay for some stuff

### Often simple operations

- Entry to swimming pool
- Entry to SPA which is not connected with room

Must generate receipt. ???

### Spa support

There are a plenty of employees, which can operate in spa. Every employee can perform single operation (like a massage) at one time.
So there is a need to assign to employee a single spa operation in given time.

For now I don't know who is responsible to assign this. 

### Reports  
 
There are a lot of different report types:

- daily
- weekly
- monthly

All of them consist of gains and looses in given period. Reports are truly screwed up, but for now, I don't know why. :)

### System users
There are 2 (maybe 3) user types:
- From reception
- From spa
- From restaurant?

There is no difference between users in the same group but every group has different capabilities.
