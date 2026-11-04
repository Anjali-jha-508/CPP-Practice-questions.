# Program 14

Write a CPP program to create a class Calculator and define arithmetic functions outside the class.

```cpp 
#include <iostream>
#include <string>
using namespace std;

class Calculator {
public:
    int num1, num2, sum, diff, mul, div;

    void input();
    void calculate();
    void display();
};

void Calculator::input() {
    cout << "To perform arithematic calculations on two numbers:" << endl;
    cout << "Enter the first number: ";
    cin >> num1;
    cout << "Enter the second number: ";
    cin >> num2;
} 
void Calculator::calculate() {
    sum = num1 + num2;
    diff = num1 - num2;
    mul = num1 * num2;
    div = num1 / num2;
}
void Calculator::display() {
    cout << endl << "The numbers entered are: " << num1 << " and " << num2 << endl;
    cout << "Their arithematic calculations are as follows:" << endl;
    cout << endl << "The sum of " << num1 << " and " << num2 << " is: " << sum << endl;
    cout << "The difference of " << num1 << " and " << num2 << " is: " << diff << endl;
    cout << "The product of " << num1 << " and " << num2 << " is: " << mul << endl;
    cout << "The quotient of " << num1 << " and " << num2 << " is: " << div << endl;
}

int main() {
    Calculator calc;
    calc.input();
    calc.calculate();
    calc.display(); 
return 0;
} 
```
---

### Output

```text
To perform arithematic calculations on two numbers:
Enter the first number: 4
Enter the second number: 5

The numbers entered are: 4 and 5
Their arithematic calculations are as follows:

The sum of 4 and 5 is: 9
The difference of 4 and 5 is: -1
The product of 4 and 5 is: 20
The quotient of 4 and 5 is: 0
```
> In this, the division of 4 by 5 gives 0, because the quotient is to be obtained in the integer form. 
---
 
<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program12.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program14.md">Next →</a>
    </td>
  </tr>
</table> 
