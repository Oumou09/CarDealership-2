# Car Dealership 2 

## Description of the Project
This Java console application is an extension of a car dealership management system. In this phase, we added Sales and Lease functionality to simulate real dealership operations.

Purpose: Allow a dealership user (salesperson or manager) to sell or lease a vehicle to a customer, generate a contract, and automatically remove that vehicle from inventory.

Intended Users: Dealership employees using a command-line terminal to manage vehicle transactions.

Main Features:View and search vehicle inventory

- Sell or lease a vehicle based on customer input
- Generate and save a SalesContract or LeaseContract
- Automatically remove sold/leased vehicles from inventory
- Persist contracts and inventory to files



## User Stories

List the user stories that guided the development of your application. 

- As a user, I want contracts to store basic customer and vehicle info so that all transactions are tracked consistently.
- As a user, I want the system to calculate total price and monthly payments based on the type of contract so that I always see the right financial details.

## Setup
Prerequisites
IntelliJ IDEA
Java SDK (JDK 17 or later)

Running the Application in IntelliJ
Open IntelliJ IDEA.
Select Open and choose your Workshop 5 project folder.
Allow the IDE to index and set up the project.
Locate the main file (Program.java or similar).
Right-click and select Run to start the dealership CLI.

Technologies Used
Java 17+
IntelliJ IDEA Community Edition
Plain text files for contract and inventory storage

Core Classes
Contract (abstract): Base class for all contracts
SalesContract: Adds finance, fees, and tax logic
LeaseContract: Handles lease-specific pricing and vehicle age check
ContractDataManager: Saves contracts to a file
Dealership / Vehicle: Manage vehicle data and list
UserInterface: Updated to support contract creation and vehicle removal

#
## Future Work
Future Enhancements
Load and display saved contract history

Support for editing or canceling contracts

Improved user input validation and formatting

Integrate with a simple database for persistence

Resources
Workbook 5: Inheritance and Polymorphism in Java
JavaDocs for ArrayList, Scanner, LocalDate
Java File I/O (Oracle)

Oumou Diallo – Developer 


Thanks to Raymond Maroun and my classmates for all the help.


