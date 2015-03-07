# Bank-Application
CS535: Object Oriented Designed application for banking purpose.
ProgrammingLanguage: Smalltalk

The bank account balances are to be currency objects. The currency class does addition and subtraction without floating
point round off. A currency object is created from a string and a number.
Currency objects can be added/subtracted. And numbers can be added/subtracted to/from
currency objects. Currency objects are comparable. Currency objects prints themselves out as dollars

Bank has types of customers, normal, preferred, premium and gold. Preferred customers get overdraft protection. 
When normal customers try to withdraw more money than is in their account the transaction is cancelled and the customer is charged a $5.00 fee.
The fee could make the account balance go negative.
Preferred customers are allowed withdraw $1,000.00 more than their account holds without penalty. 
Any transaction that makes the balance of a preferred customers balance become less than -$1,000.00 is cancelled and the customer is charged a $3.00 fee.


When you deposit a check into  account the money is put on hold until the the check clears. Until the check clears account has two
balances. First is the total balance. That is the sum of all income minus the sum of all expenditures.
Second is the available balance.

Banks is able to handle transactions in different currencies: US dollars, Mexican Pesos and Canadian dollars.
