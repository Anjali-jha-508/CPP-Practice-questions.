# Program 18

Write a CPP program to create a class Calculator and create an object to perform addition, subtraction, multiplication, and division. 

```cpp 
#include <iostream>
#include <string> 
using namespace std;

class Calculator {
public:
  int num1, num2, sum, diff, product, quot;
  
  void input() {
    cout << "Enter number 1: ";
    cin >> num1;
    cout << "Enter number 2: ";
    cin >> num2; 
  }

  void addition() {
    sum = num1+ num2;
  }

  void subtraction() {
    diff = num1 - num2;   
  }

  void multiplication()  {
    product = num1 * num2;
  }

  void division() {
    quot = num1 / num2 ;  
  }

  void display() {
    cout << endl << "----DIFFERENT ARTITHEMATIC OUTPUTS---" << endl;
    cout << "Addition of " << num1 << " & " << num2 << " is: " << sum << endl;
    cout << "Subtraction of " << num1 << " & " << num2 << " is: " << diff << endl;
    cout << "Multiplication of " << num1 << " & " << num2 << " is: " << product << endl;
    cout << "Division of " << num1 << " & " << num2 << " is: " << quot << endl;
  }
};

int main() {
  Calculator c1;
  c1.input();
  c1.addition();
  c1.subtraction();
  c1.multiplication();
  c1.division();
  c1.display(); 
return 0;
}
```

### Output

```text
Enter number 1:     (example 10; press enter)
Enter number 2:     (example 8; press enter)

----DIFFERENT ARTITHEMATIC OUTPUTS---
Addition of 10 & 8 is: 18
Subtraction of 10 & 8 is: 2
Multiplication of 10 & 8 is: 80
Division of 10 & 8 is: 1
--------------------------------------
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program17.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program19.md">Next →</a>
    </td>
  </tr>
</table>

