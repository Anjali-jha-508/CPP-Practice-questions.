# Program 3

Write a CPP program to create a class Calculator with functions inside the class for basic arithmetic operations.  

```cpp 
#include <iostream>
#include <string>
using namespace std;

class Calculator{
public:
   int num1, num2, add, sub, mul, div;
void userinput() {
      cout << "To perform the artihmetic operations" << endl;
      cout << "Enter the first number: ";
      cin >> num1;  
      cout << "Enter the second number: ";
      cin >> num2; 
} 
int addition() {
      add = num1 + num2;
      return add;
} 
int subtraction() {
      sub = num1 - num2;
      return sub;
} 
int multiplication(){
      mul = num1 * num2;
      return mul;  
} 
int division() {
      div = num1 / num2;
      return div;  
} 
void display() {
       cout << "Arithematic operations on " << num1 << " and " << num2 << " is as follows: " << endl;
       cout << "Addition: " << addition() << endl;
       cout << "Subtraction: " << subtraction() << endl;
       cout << "Multiplication: " << multiplication() << endl;
       cout << "Division: " << division() << endl;
}
};

int main() {
  Calculator calc;
  calc.userinput();
  calc.display();    
return 0;
}  
```
---

### Output

```text
To perform the artihmetic operations
Enter the first number: 5
Enter the second number: 6

Arithematic operations on 5 and 6 is as follows: 
Addition: 11
Subtraction: -1
Multiplication: 30
Division: 0  
```

> Here the division of 5 and 6 gives 0 as the output is in interger form.  
>
> To get the exact output, the input and division must be in <kbd>float</kbd> or <kbd>double</kbd>

---

<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program2.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program4.md">Next →</a>
    </td>
  </tr>
</table>
