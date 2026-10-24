# Program 5

Write a CPP program to create a class Addition with two data members. Take two numbers as input and display their sum using a member function.

```cpp
#include <iostream> 
using namespace std;

class Addition {
public: 
  int num1, num2, sum;

void userinput() {
    cout << "Enter number 1: ";
    cin >> num1;
    cout << "Enter number 2: ";
    cin >> num2;
}

void add() {
  sum = num1 + num2;
}

void display() {
  cout << "Addition of " << num1 << " and " << num2 << " is: " << sum << endl; 
}
};

int main() {
  Addition a1;
  a1.userinput();
  a1.add();
  a1.display();
return 0;
}
```

### Output

```text
Enter number 1: (example 2, press enter)
Enter number 2 : (example 100, press enter)
(after pressing enter)
Addition of 2 and 100 is: 102
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program4.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program6.md">Next →</a>
    </td>
  </tr>
</table>
