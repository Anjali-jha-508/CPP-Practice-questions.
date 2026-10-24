# Program 10

Write a CPP program to create a class BankAccount with account number, account holder name, and balance. Display the account details.  

```cpp
#include <iostream> 
#include <string>
using namespace std;

class BankAccount {  
public: 
  string name;
  int accNo, balance;

void input() {
    cout << "Enter your name: ";
    cin >> name;
    cout << "Enter your account number: ";
    cin >> accNo;
    cout << "Enter balance in your bank account: ";
    cin >> balance;
}    
 
void display() {
  cout << "Account holders name: " << name << endl;  
  cout << "Account number: " << accNo << endl; 
  cout << "Balance available: " << balance << endl;  
}
};

int main() {     
  BankAccount b1;
  b1.input();
  cout << endl << "---ACCOUNT DETAILS---" << endl;
  b1.display();
return 0;
}
```

### Output

```text 
Enter your name:      (example Alex, press enter)
Enter your account number:      (example 908989, press enter)
Enter balance in your bank:      (example 950000, press enter)
(after pressing enter)

---ACCOUNT DETAILS---
Account holder's name: Alex
Account number: 908989
Balance available: 950000
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program9.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program11.md">Next →</a>
    </td>
  </tr>
</table>

