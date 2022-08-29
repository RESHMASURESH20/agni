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

DATAS NEED TO BE INSERTED WHILE INSERTING THE MOVIE
1.name:Cobra
desc:A mathematician genius Mathi who has another identity Cobra who commits intelligent crimes using Maths.
video:https://www.youtube.com/embed/8ScCLfGGOPY
Image:https://assets-in.bmscdn.com/iedb/movies/images/mobile/thumbnail/xlarge/cobra-et00103189-1656312188.jpg


2.Name:Sita Ramam
desc:A long-lost letter must find its way to the recipient twenty years later. A rabble-rouser learns a lesson in humility and love along the way.
Video:https://www.youtube.com/embed/Ljk6tGZ1l3A
Image:https://assets-in.bmscdn.com/iedb/movies/images/mobile/thumbnail/xlarge/sita-ramam-et00329656-30-05-2022-06-32-41.jpg

3.Name:Viruman
Desc:Viruman is a Tamil movie directed by M Muthaiah, starring Karthik Sivakumar in the lead role.
Video:https://www.youtube.com/embed/aRx4-fsJ5uE
Image:https://assets-in.bmscdn.com/iedb/movies/images/mobile/thumbnail/xlarge/viruman-et00321392-14-01-2022-01-07-39.jpg

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
   
