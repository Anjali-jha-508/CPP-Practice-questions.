# Program 4

Write a CPP program to create a class Employee with data members name and salary. Take input and display the employee details.

```cpp
#include <iostream> 
#include <string>
using namespace std;

class Employee {
public: 
  string name;
  int salary;

void userinput() {
    cout << "Enter name of the employee: ";
    cin >> name;
    cout << "Enter salary of the employee: ";
    cin >> salary;
}
 
void display() {
  cout << "Employees name is: " << name << endl; 
  cout << "Employees salary is: " << salary << endl;
}
};

int main() {
  Employee e1;
  e1.userinput();
  e1.display();
return 0;
}
```

### Output

```text
Enter name of the employee: (example Alex, press enter)
Enter salary of the employee: (example 1000000, press enter)
(after pressing enter)
Employees name is: Alex
Employees salary is: 100000
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program3.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program5.md">Next →</a>
    </td>
  </tr>
</table>


