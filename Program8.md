# Program 8

Write a CPP program to create a class Number with a function inside the class to find the factorial of a number. 

```cpp 
#include <iostream>
using namespace std;

class Number {
public:
  int n, fac;
  
  void input() {
    cout << "Enter the number whose factorial is to be calculated: ";
    cin >> n; 
  } 

  void calcFac() {
    fac = 1;
    for(int i = 1; i <= n; i++) {
      fac = fac * i;
    }
  }  

  void display() {
    cout << "Factorial of " << n << " is " << fac;  
  }
};

int main(){
  Number n1;
  n1.input();
  n1.calcFac();
  n1.display();
return 0;  
}

```
---

### Output

```text
Enter the number whose factorial is to be calculated: 5
Factorial of 5 is 120 
```
> Factorial of 0 is always 1, therefore the value of int starts from 0. If started from 0 it will give output as 0, as anything multiplied to zero remains 0.
>
> Initially the value of fac is 1, i.e the factorial value of 0. (0! = 1)
---

<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program7.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program9.md">Next →</a>
    </td>
  </tr>
</table>
