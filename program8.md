# Program 8

Write a CPP program to create a class Number with a data member num and a member function to check whether the number is odd or even.

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

### Output

```text
To check whether the number is even or odd.
Enter the number:      (example 2, press enter)
(after pressing enter)
2 is even.
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program7.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program9.md">Next →</a>
    </td>
  </tr>
</table>
