<h1 align="center">Bus Reservation System</h1>


This is a simple Bus Reservation System programmed using Cpp .This program allows you to add bus details,then you can reserve a bus seat according to vacant seat available.One can check for list for vacant seats in a bus.It also allows you to see the available bus for now.
This is a simple implementation of c++ code using class and structure. 

## How to run

Before running make sure you are having an c++ ide for windows users and g++ compiler installed for linux users.For windows user just open the file with any cpp ide and just compile and run.For unix users first navigate to the directory where this ```busrsm.cpp ``` file stored and then run the follwoing commands in terminal.

```C++
g++ [filename.cpp]
./a.out # unix
a.exe # windows
```
Normal Input/Output format for the code:
```C

sirbor@Dominics-MacBook-Pro ~ % cd Bus
sirbor@Dominics-MacBook-Pro Bus % cd Bus-Reservation-System
sirbor@Dominics-MacBook-Pro Bus-Reservation-System % ls
LICENSE					busResOutput
README.md				busReservation.cpp
Screenshot from 2019-09-16 21-52-39.png	sm.png
a.out
sirbor@Dominics-MacBook-Pro Bus-Reservation-System % g++ busReservation.cpp
sirbor@Dominics-MacBook-Pro Bus-Reservation-System % ./a.out
---------------------------------------------------------------------------
				****SM Bus Travel Agency****

---------------------------------------------------------------------------

***************************************************************************


			1.Add new Bus Details:
			2.Reserve your seats:
			3.Show the available seats in a bus:
			4.Buses Available Now: 
			5.Exit
***************************************************************************

			Enter your choice:-> 1
***************************************************************************
Enter bus no: 123

Enter Driver's name: Peter

Arrival time : 10:15AM

Departure: 10:25AM

From: 			NAIROBI

To: 			KIAMBU

***************************************************************************


			1.Add new Bus Details:
			2.Reserve your seats:
			3.Show the available seats in a bus:
			4.Buses Available Now: 
			5.Exit
***************************************************************************

			Enter your choice:-> 1
***************************************************************************
Enter bus no: 245

Enter Driver's name: Paul

Arrival time : 10:58AM

Departure: 11:04AM

From: 			THIKA

To: 			KIAMBU

***************************************************************************


			1.Add new Bus Details:
			2.Reserve your seats:
			3.Show the available seats in a bus:
			4.Buses Available Now: 
			5.Exit
***************************************************************************

			Enter your choice:-> 4
***************************************************************************
***************************************************************************
Bus no: 	123
Driver: 	Peter		Arrival time: 	10:15AM	Departure Time: 	10:25AM
From: 		NAIROBI		To: 			KIAMBU
***************************************************************************
___________________________________________________________________________
***************************************************************************
Bus no: 	245
Driver: 	Paul		Arrival time: 	10:58AM	Departure Time: 	11:04AM
From: 		THIKA		To: 			KIAMBU
***************************************************************************
___________________________________________________________________________

***************************************************************************


			1.Add new Bus Details:
			2.Reserve your seats:
			3.Show the available seats in a bus:
			4.Buses Available Now: 
			5.Exit
***************************************************************************

			Enter your choice:-> 3
***************************************************************************
Enter bus no: 123
***************************************************************************

Bus no: 	123
Driver: 	Peter		Arrival time: 	10:15AM	Departure time:10:25AM
From: 		NAIROBI		To: 		KIAMBU
***************************************************************************

    1.     Empty    2.     Empty    3.     Empty    4.     Empty
    5.     Empty    6.     Empty    7.     Empty    8.     Empty
    9.     Empty   10.     Empty   11.     Empty   12.     Empty
   13.     Empty   14.     Empty   15.     Empty   16.     Empty
   17.     Empty   18.     Empty   19.     Empty   20.     Empty
   21.     Empty   22.     Empty   23.     Empty   24.     Empty
   25.     Empty   26.     Empty   27.     Empty   28.     Empty
   29.     Empty   30.     Empty   31.     Empty   32.     Empty

There are 32 seats empty in Bus No: 123
***************************************************************************


			1.Add new Bus Details:
			2.Reserve your seats:
			3.Show the available seats in a bus:
			4.Buses Available Now: 
			5.Exit
***************************************************************************

			Enter your choice:-> 2
***************************************************************************
Bus no: 245

Seat Number: 31
Enter passanger's name: Sirbor

***************************************************************************


			1.Add new Bus Details:
			2.Reserve your seats:
			3.Show the available seats in a bus:
			4.Buses Available Now: 
			5.Exit
***************************************************************************

			Enter your choice:-> 3
***************************************************************************
Enter bus no: 245
***************************************************************************

Bus no: 	245
Driver: 	Paul		Arrival time: 	10:58AM	Departure time:11:04AM
From: 		THIKA		To: 		KIAMBU
***************************************************************************

    1.     Empty    2.     Empty    3.     Empty    4.     Empty
    5.     Empty    6.     Empty    7.     Empty    8.     Empty
    9.     Empty   10.     Empty   11.     Empty   12.     Empty
   13.     Empty   14.     Empty   15.     Empty   16.     Empty
   17.     Empty   18.     Empty   19.     Empty   20.     Empty
   21.     Empty   22.     Empty   23.     Empty   24.     Empty
   25.     Empty   26.     Empty   27.     Empty   28.     Empty
   29.     Empty   30.     Empty   31.    Sirbor   32.     Empty

There are 31 seats empty in Bus No: 245
The seat no 31 is reserved for Sirbor.
***************************************************************************


			1.Add new Bus Details:
			2.Reserve your seats:
			3.Show the available seats in a bus:
			4.Buses Available Now: 
			5.Exit
***************************************************************************

			Enter your choice:-> 5
***************************************************************************
Successfully Logged out from the Application. Visit Again!
<Thanks You :)>
Created By Dominic Bor
sirbor@Dominics-MacBook-Pro Bus-Reservation-System % 

```

## Usage

```CPP


  void addnewbus() # Used to add a new bus details

  void allotment(); #used to allot a set to an passenger

  void empty(); # to check if the buses are empty

  void show(); #shows avialble bus seats

  void avail(); #shows all avialable buses

  void position(int i); #to get the all reserved bus seats
```
