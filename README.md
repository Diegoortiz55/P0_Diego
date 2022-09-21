# P0_Diego

This is a console banking application written in C# using .Net Core framework and ADO.Net. The main functionalities of this program include two user menus with separate
options for each. The admin menu allows an individual to view all account details, create an account, make withdrawals, deposits, and transfers for users,
and the ability to lock or unlock a user account. The user menu allows an individual to make withdrawals, deposits, and transfers, view account details,
and change their password. The program utilizes client side validation for login credentials and all monetary functions. The program will also automatically
lock a user account after 3 failed login attempts. Exception handling is utilized all throughout the program in order to send user friendly messages when
incorrect inputs are attempted. Methods for login, transactions, and account information are kept in separate classes in order to keep roles and responsibilities
clearly distinct.
