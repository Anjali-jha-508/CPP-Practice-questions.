# Program 11

Write a CPP program to create a class Number with a function square() inside the class to calculate the square of the number.

```cpp 
#include <iostream>  
using namespace std;

class Number {
public:
  int num, square;
  
  void input() {
    cout << "Enter a number to calculate its square: ";
    cin >> num; 
  }

  void calcSq() {
    square = num * num;
    cout << "Square of " << num << " is " << square;      
  } 
};

int main() {
  Number n1;
  n1.input();
  n1.calcSq();
return 0;
} 
```
---

### Output

```text
Enter a number to calculate its square: 9
Square of 9 is 81
```
---
 
<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program10.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program12.md">Next →</a>
    </td>
  </tr>
</table> 
