# Atm_stimulation_software
I developed this atm stimulation software using java .In which I have created two classes bank controller.java class and user class.java .. User class is use for creating the database using arraylist .the arraylist contain four columns or four parameters  (account id(8 digit) ,name,pin(4 digit), balance). We use getters for all the 4 parametrs but use setters for only two parametrs that is balance and pin because we may need to change them if required.getters and setters are used for privte acess of data. Bank controller java contains two switch cases.. Switch 1 (the first switch conatin two cases 1st Sign up page and 2nd login page. sign up tells you to enter first name and last name  and then its generates random account and random pin using help of random library. (Formula used :- int random_acc = Math.random()*(end - start +1) + start ). the random pin and account number that is generated here is used for login into your account.

(Download the code, compile & run it in command prompt for better experience.)

Video demonstration : https://youtu.be/7ji2pZKPW98

Features :
- User can create a new account, or login into existing account.
- The code automatically generates random Account number and Pin while creating a new account.
- User can login using Account number and Pin, and perform operations like updating pin, balance inquiry, withdraw and deposit amount, logout.
- During every login and logout, the code generates Success message with a date-time stamp.
- It can store multiple accounts of different users in single execution.
- For any wrong input, it generates a warning and ends the session.

Technique :
- Created using JAVA Programming.
- ArrayList for creating a database.
- Concept of method and objects, for inputting and extracting data.
- Getters and Setters for private access to data.
- Date and DateFormat class for generating time-date stamp.
- Math.random() function for generating random Account no. and Pin.
- Try catch block for exception handling.

