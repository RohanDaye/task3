This Java program simulates a simple ATM (Automated Teller Machine) system. It consists of three classes: BankAccount, ATM, and ATMApp. Here's a breakdown of each class:

BankAccount Class:

This class represents a bank account with a private balance.
It has a constructor to initialize the account with an initial balance.
Methods include getBalance to retrieve the current balance, deposit to add funds, and withdraw to subtract funds if the balance is sufficient.
ATM Class:

This class interacts with the BankAccount class to perform ATM operations.
It has a constructor that takes a BankAccount as a parameter.
displayMenu prints the ATM menu with options to check balance, deposit, withdraw, and exit.
processUserChoice takes a user choice as input and performs the corresponding action.
ATMApp Class:

This class contains the main method and serves as the entry point for the program.
It creates an instance of the BankAccount class with an initial balance of $1000 and an instance of the ATM class.
It uses a while (true) loop to repeatedly display the ATM menu, take user input, and process the user's choice.
The program continues running until the user chooses to exit (choice == 4). The user can check their balance, deposit money, withdraw money (if the balance is sufficient), and exit the ATM.
