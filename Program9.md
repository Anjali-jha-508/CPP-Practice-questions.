# Program 9

Write a CPP program to create a class BankAccount with functions inside the class to deposit cash, check balance and withdraw money. 

```cpp 
#include <iostream>
#include <string>
using namespace std;

class BankAccount {
public:
string accountHolder;
string accountNumber;
double balance, amount;

// Function to deposit cash
void deposit() {
  if (amount > 0) {
  balance += amount;
  cout << "Successfully deposited $" << amount << "\n";
  } 
  else {
  cout << "Invalid deposit amount!\n";
  } 
}
// Function to withdraw money
void withdraw() {
  if (amount <= 0) {
  cout << "Invalid withdrawal amount!\n";
  } 
  else if (amount > balance) {
  cout << "Insufficient funds! Current balance: $" << balance << "\n";
  } 
  else {
  balance -= amount;
  cout << "Successfully withdrew $" << amount << "\n";
  }
}
// Function to check and display balance
void checkBalance() const {
  cout << "\n-----------------------------\n";
  cout << "Account Holder: " << accountHolder << "\n";
  cout << "Account Number: " << accountNumber << "\n";
  cout << "Current Balance: $" << balance << "\n";
  cout << "-----------------------------\n";
}
};

int main() { 
  BankAccount myAccount;  
  myAccount.accountHolder = "Alex Mercer";
  myAccount.accountNumber = "BAC123456789";
  myAccount.balance = 500.00;

  int choice;
  double amount;
    do {
      cout << "\n=== ATM Banking Menu ===\n";
      cout << "1. Check Balance\n";
      cout << "2. Deposit Cash\n";
      cout << "3. Withdraw Money\n";
      cout << "4. Exit\n";
      cout << "Enter your choice (1-4): ";
      cin >> choice;

      switch (choice) {
        case 1:
        myAccount.checkBalance();
        break;
        case 2:
        cout << "Enter amount to deposit: $";
        cin >> amount;
        myAccount.deposit();
        break;
        case 3:
        cout << "Enter amount to withdraw: $";
        cin >> amount;
        myAccount.withdraw();
        break;
        case 4:
        cout << "Thank you for using our banking services. Goodbye!\n";
        break;
        default:
        cout << "Invalid choice! Please try again.\n";
      }
    } while (choice != 4);
    
return 0;
}
```
---

### Output

```text
=== ATM Banking Menu ===
1. Check Balance
2. Deposit Cash
3. Withdraw Money
4. Exit
Enter your choice (1-4): 1

-----------------------------
Account Holder: Alex Mercer
Account Number: BAC123456789
Current Balance: $500
-----------------------------

=== ATM Banking Menu ===
1. Check Balance
2. Deposit Cash
3. Withdraw Money
4. Exit
Enter your choice (1-4): 2
Enter amount to deposit: $500
Successfully deposited $500

=== ATM Banking Menu ===
1. Check Balance
2. Deposit Cash
3. Withdraw Money
4. Exit
Enter your choice (1-4): 3
Enter amount to withdraw: $900
Successfully withdrew $900

=== ATM Banking Menu ===
1. Check Balance
2. Deposit Cash
3. Withdraw Money
4. Exit
Enter your choice (1-4): 4
Thank you for using our banking services. Goodbye!  
```
---
> In this program, various terms like switch, do...while are used to write the code.

> As per our question we have to operate on 3 different banking terms. To execute these we created three functions inside the class. As there are 3 different options we will give the user options between what he could operate, the 4th option is to exit. This operation is carried using switch statement which is inserted in the do while loop, so that it will keep asking the user until he himself exits the operation.
 
> Here in the output, the loop has continued till the exit option was not selected. 
---

<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program8d">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program10.md">Next →</a>
    </td>
  </tr>
</table>
