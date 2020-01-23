# Credit-Card-Processor-

the goal of this project is to implement a
program that will add new credit card accounts, process charges and credits
against them, and display summary information.

## Input Assumptions:

- All input will be valid -- there's no need to check for illegal characters
  or malformed commands.
- All input will be space delimited.
- Credit card numbers may vary in length up to 19 characters.
- Credit card numbers will always be numeric.
- Amounts will always be prefixed with "$" and will be in whole dollars (no
  decimals).
- Accounts will be validated by a Luhn 10 validation algorithm 

In my process of constructing this program, my first thought was "How am i going to hold this information?" my options included:
-sql
-a dictionary
-simple array
-JSON

I stuck with the dictionary because it is possible to make a mini database/array with a class dictionary 

From there, it was a matter of mapping the add, charge, credit, and summary functions to key values of the dictionary and the text inputs for the program 

I chose python because i wanted to work to improve my proficiency in the language syntax structure. I originally made the choice between doing it in Python or JavaScript

Upon running the program, users can enter:
- "add" followed by a name, account number, and a limit 
- "charge" followed by the name account number, and an amount they wish to add
- "credit" followed by the name account number, and an amount they wish to add
in the command terminal or even the python IDLE shell
