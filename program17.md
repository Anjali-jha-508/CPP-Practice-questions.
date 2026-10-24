# Program 17

Write a CPP program to create a class Employee and create an object to calculate the annual salary of an employee. 

```cpp 
#include <iostream>
#include <string> 
using namespace std;

class Employee {
public:
  string name;
  int empID;
  double monthlySalary, annualSalary;
  
  double calculateAnnualSalary() {
  return monthlySalary * 12;
  }

  void displayEmployeeDetails() {
  cout << "\n----- Employee Financial Details -----\n";
  cout << "Employee Name  : " << name << "\n";
  cout << "Employee ID    : " << empID << "\n";
  cout << "Monthly Salary : $" << monthlySalary << "\n";
  cout << "Annual Salary  : $" << calculateAnnualSalary() << "\n";
  cout << "--------------------------------------\n";
  }
};

int main() {
  Employee e1;

  //taking user inputs:
  cout << "Enter Employee Name: ";
  getline(cin, e1.name);
  cout << "Enter Employee ID: ";
  cin >> e1.empID;
  cout << "Enter Monthly Salary: ";
  cin >> e1.monthlySalary;
 
  e1.displayEmployeeDetails();
return 0;
}
```

### Output

```text
Enter Employee Name:        (example: Alex Michel, press enter)
Enter Employee ID:          (example: 1209890, press enter)
Enter Monthly Salary:       (example: 75000, press enter)

----- Employee Financial Details -----
Employee Name  : Alex Michel
Employee ID    : 1209890
Monthly Salary : $75000
Annual Salary  : $900000
--------------------------------------
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program16.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program18.md">Next →</a>
    </td>
  </tr>
</table>

