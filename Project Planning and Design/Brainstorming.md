Desired Features:
Basic approximator that gives an approximate lease payment with a minimum of information needed. This should be formatted like a wizard that asks questions

Being able to calculate a residual percentage from national advertisements
-Have a full featured calculator that allows user full control over all variables
-Have a specific Calculator for each State Laws
-Allow user to save a local database with vehicle information that calculator can pull from
-Allow user to create custom calculator

Ideas about Project Structure
-Have a fundamental class that calculates payment and various aspects of lease from variables
-Have separate built in classes that extend the fundamental calculation class and preassign certain variables. They will have their own constructors that take all remaining necessary variables. Good use of these will be for different states.

UI structure:
-Main Menu
-Wizard which guides user through entering basic information for a simple approximation of a basic lease payment
-UI which allows users to change all variables, see the resulting calculations and save/load current lease calculation
-UI which allows user to modify a local database that contains leasing information about various cars. 
(There should be either a way to load in a car from a local database into the main calculation UI or a way to take a car from the database screen into the main calculation screen).
