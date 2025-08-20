# Bank Account System  

 This project is a simple Object-Oriented Programming (OOP) implementation of a banking system in Python.  
 It demonstrates encapsulation, inheritance, getters & setters, and method overriding.  

# Features  
 
 BankAccount Class  

 Private attributes: __account_number, __account_holder, __balance  

# Methods:  

 Deposit(amount) → Adds money to the account  

Withdraw(amount) → Deducts money if balance is sufficient  

Display() → Shows account details (number, holder, balance)  

GetBalance() → Getter for balance  

SetBalance(new_balance) → Setter for balance  

SavingsAccount Class (Inherits from BankAccount):  

Adds an __interest_rate attribute (default 5%)  

ApplyInterest() → Applies interest to the balance using getter and setter methods  

# Output  
To get an output write the piece of code below:  
```python
obj = SavingsAccount("12345", "Alice", 1000)  # Create a Savings Account  
obj.Display()  # Display account details  
obj.Deposit(500)  ## Deposit money  
obj.Withdraw(200)  # Withdraw money  
obj.ApplyInterest() # Apply interest  
obj.Display() # Final details
```
you should get the result below:  
```python
Account Number: 12345  
Account Holder: Alice  
Balance: 1000  
You have deposited: 500 The new balance is: 1500  
You have withdrawn: 200 The new balance is: 1300  
With Interest: 1365.0  
Account Number: 12345  
Account Holder: Alice  
Balance: 1365.0  
```
