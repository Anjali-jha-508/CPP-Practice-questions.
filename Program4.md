# Program 4

Write a CPP program to create a class Number with a function inside the class to check whether a number is even or odd.  

```cpp 
#include <iostream> 
using namespace std;

class Number {  
public: 
  int num;

void getNum() {
    cout << "Enter the number: ";
    cin >> num;
}    
 
void display() {
  if(num % 2 == 0) {
    cout << num << " is even." << endl; 
  }     
  else {
    cout << num << " is odd." << endl; 
  }
}
};

int main() {
  cout << "To check whether the number is even or odd." << endl; 
  Number n1;
  n1.getNum();
  n1.display();
return 0;
} 
```
---

### Output

```text
To check whether the number is even or odd.
Enter the number:      (example 2, press enter)
(after pressing enter)
2 is even.
```
---

> This same code we saw in the class and object section too, sometimes code is the easiest, but the way in which it is asked may confuse us.


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program3.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program5.md">Next →</a>
    </td>
  </tr>
</table>
