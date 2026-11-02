# Program 6

Write a CPP program to create a class Employee with a function inside the class to calculate annual salary.

```cpp 
#include <iostream>
#include <string>
using namespace std;

class Employee {
pubic:
  string name;
  int empId, mnthSal, bonus, total_salary;

void userinput() {
  cout << "---ENTER EMPLOYEE DETAILS---" << endl;
  cout << "Employee name: ";
  getline(cin, name);
  cin.ignore;
  cout << "Employee Id: ";
  cin >> empId;
  cout << "Monthly Salary: ";
  cin >> mnthSal;
  cout << "Annual Bonus: ";
  cin >> bonus;
}

void calcTsal() {
  total_salary = (mnthSal * 12) + bonus;
}

void display {
  cout << "---EMPLOYEE DETAILS---";
  cout << "Name: " << name << endl;
  cout << "ID: " << empId << endl;
  cout << "Total Salary: " << total_salary << endl;
}
};

int main() {
  Employee e1;
  e1.userinput();
  e1.display();
return 0;
}   
   
```
---

### Output

```text
 
```
---

> We came across this code earlier too, during class and object.


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program5.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program7.md">Next →</a>
    </td>
  </tr>
</table>



