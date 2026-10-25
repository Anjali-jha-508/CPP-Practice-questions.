# Program 21

Write a CPP program to create a class Employee and create multiple objects to store and display details of five employees.  

```cpp 
#include <iostream>
#include <string>
using namespace std;

class Employee {
public: 
    int id;
    string name;
    string designation;
    double salary;
 
    // Function to take input for an employee
    void input() {
        cout << "Enter ID: ";
        cin >> id;
        cin.ignore(); // Clear the input buffer before reading a string
        
        cout << "Enter Name: ";
        getline(cin, name);
        
        cout << "Enter Designation: ";
        getline(cin, designation);
        
        cout << "Enter Salary: ";
        cin >> salary;
    }

    // Function to display employee details
    void display()  {
        cout << "--------------------------------------------------------\n";  
        cout << id << "\t\t" 
             << name << "\t\t" 
             << designation << "\t\t" 
             << salary << "\n";
    }
};

int main() {
    
    Employee e1, e2, e3, e4, e5;
    cout << "--- Enter Employee Records ---" << endl;
    cout << "\nEnter details for Employee 1:\n";
    e1.input();
    cout << "\nEnter details for Employee 2:\n";
    e2.input();
    cout << "\nEnter details for Employee 3:\n";
    e3.input();
    cout << "\nEnter details for Employee 4:\n";
    e4.input();
    cout << "\nEnter details for Employee 5:\n";
    e5.input();

    cout << "\n--- Employee Details ---\n";
    cout << "ID\t\tName\t\tDesignation\tSalary\n";
    e1.display();
    e2.display();   
    e3.display();
    e4.display();
    e5.display();

    return 0;
}
```

### Output

```text
EXAMPLE:

--- Enter Employee Records ---

Enter details for Employee 1:
Enter ID: 890
Enter Name: Alex
Enter Designation: HR
Enter Salary: 900000

Enter details for Employee 2:
Enter ID: 789
Enter Name: Michel
Enter Designation: VP
Enter Salary: 800000

Enter details for Employee 3:
Enter ID: 675
Enter Name: Ryuk
Enter Designation: Chancellor
Enter Salary: 750000 

Enter details for Employee 4:
Enter ID: 645
Enter Name: Yagami
Enter Designation: President
Enter Salary: 505000

Enter details for Employee 5:
Enter ID: 346
Enter Name: Gabi
Enter Designation: Manager
Enter Salary: 450000

--- Employee Details ---
ID              Name            Designation     Salary
--------------------------------------------------------
890             Alex            HR              900000
--------------------------------------------------------
789             Michel          VP              800000
--------------------------------------------------------
675             Ryuk            Chancellor      750000
--------------------------------------------------------
645             Yagami          President       505000
--------------------------------------------------------
346             Gabi            Manager         450000
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program20.md">← Previous</a>
    </td>
  </tr>
</table>

