# Program 6

Write a CPP program to create a class Calculator with member functions for addition and substraction.

```cpp
#include <iostream> 
using namespace std;

class Calculator {
public: 
  int num1, num2, sum, diff;

void userinput() {
    cout << "Enter number 1: ";
    cin >> num1;
    cout << "Enter number 2: ";
    cin >> num2;
}

void add() {
  sum = num1 + num2;
}

void sub() {
  diff = num1 - num2;
}

void display() {
  cout << "Addition of " << num1 << " and " << num2 << " is: " << sum << endl;
  cout << "Subtraction of " << num1 << " and " << num2 << " is: " << diff << endl; 
}
};

int main() {
  Calculator c1;
  c1.userinput();
  c1.add();
  c1.sub();
  c1.display();
return 0;
}
```

### Output

```text
Enter number 1: (example 2, press enter)
Enter number 2 : (example 100, press enter)
(after pressing enter)
Addition of 2 and 100 is: 102
Subtraction of 2 and 100 is: -98
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program5.md">← Back</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program7.md">Next →</a>
    </td>
  </tr>
</table>
