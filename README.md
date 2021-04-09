# Zuri-Training-ATM-Project-with-functions
Repository hosting source codes for the Mock ATM Project. Carried out with the use of functions. 

This file provides the codes used in proferring solutions to the Phyton assignment on Zuri Board. 

The project was executed by making use of three functions - login, register, operation and the main code block main incorporated the program flows to run the code as seen.

# The main function
The main fucntion contains the basic interface and program flow of the code. It first prints a message asking for what activity to do today and if the user enters 1, it proceeds to the login screen, 2 for the register and 0 to exit the code. 

# The register function 
The register function gets called if the user presses option 2 from the main function, and it duly asks for first name, last name and preferred account type. After the user inputs all these, he gets an accounted created with an account number generated. 

# The login function
The login functions prompts the user to enter username and password and if found in the databse created, it returns a True value and prints a welcome message and if otherwise , it prints a login failed message and returns False. 

# The operation funtion 
If login function returns true , the operation function gets called and here the user can choose between withdrawing , depositing, or lodging a complainnt. 
For depositing, if the ammount to be withdrawn is equal to or more than the initial ammount , the user gets a prompt to request an ammonunt less than that. And if successful , his balance is the difference between the initial ammount present and the ammount withdrawn. And all these are printed out . 

And if it is deposit, he gets a similar prompt as above and the balance is updated with the new deposit. 

And if he lodges a complaint, the system receives it and tells him he will be contacted soon . 

 


