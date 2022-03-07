# -Hostel-Management-System-
Implemented Hostel Management System using c++
                       OVERVIEW

	Introduction

	Hostel management system gives the correct idea of student details, building information, rooms allotment to each student and capacity of each hostel.
	It allows admin to keep record of the student’s personal detail and also related to their hostel details.
	Prepare a file that store the record of existing students with their  roll id, mobile no and their room details i.e. their respected room no and the current hostel name.
	Prepare a file to store the details about the hostels i.e. capacity, name and currently students boarding.
	Implemented a method which allow facility for transfer of rooms, hostel change.
	Rooms allotted to new students on the basis of current seat availability.


	Implementation

	Implement the hostel management system  using C++ programming language.
	Uses the concept of object oriented programming and file management system to manage the details of hostel and students.
	We have designed two class namely hostel and student to record hostels and students detail respectively.
               
                       





 	Hostel class


	Variable

     Name            Data type                            Function

      
     Name              String                           Name of hostel

    Capacity	         Int	               Total number of students the hostel can board

    Curr_num	           Int	               Number of students currently boarding in hostel


	Methods

 Name         Function
 
create()	  To take input
print()   	To print the values to output
retname()	  Returns the name
retcap()	  Returns the capacity
retcurr()  	Returns number of students boarding
inc_curr()	To increment the value of curr_num
dec_curr()	To decrement the value of curr_num





 	Student class


	Variable

 Name          Data type        function
Fname	          char	    First name of student
lname	          char	    Surname of student
hname	          char	    Name of hostel the student is currently residing at
roll_no	        int	      Name of hostel the student is currently residing at
room_no	        int	      Room Number of student
phno	          int	      Phone Number of student



	Methods

 Name                         Function
create()	                 To take input
print()	                   To print the values to output
retroll()  	               Returns the roll number
rethname()  	             Returns the hostel name
retfname()	               Returns the first name
change_room(int)	         Changes the value of roomno variable
change_hostel(string)	     Changes the value of hostel variable




