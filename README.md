# agni
FRONT END:
Use case:



Admin:

    1) Login

     2)Add movie

    3) Delete movie

Home component:

         Movie list and click view to get description component

Description component:

     We can view the   Movie Description if need to book the ticket user need to login

User login component: 

    1)Registeration of new user

    2)Login by existing account .

After login 

Booked Component:(by click login)

     1)Select  the required seats 

     2)customer details and click next 

     3)Ticket generated

4)details about the booked ticket will be displayed
BACKEND:
Steps need to be done:



Create tables with following properties:



create table userauth ( customerid serial, user_name varchar(50), password varchar(50));



create table ticketbooking(ticketid serial, customername varchar(50),movieid int,moviename varchar(50),netprice int,noofticket int ,mobilenumber varchar(50) unique);



create table seatbooking(seat serial , booked boolean,selected boolean);







Predefined value the table should have:



Table seatbooking



seat | booked | selected 

------+--------+----------

    1 | t    | f

    2 | t     | f

    3 | t     | f

    4 | f      | f

    5 | f      | f

    6 | f      | f

    7 | f      | f

    8 | f      | f

    9 | f      | f

   10 | f    | f
   
