# Program 15

Write a CPP program to create an object of class Student and display student details.

```cpp
#include <iostream> 
#include <string>
using namespace std;

class Student{
public:
  string name, surname;
  int age;
 
void display() {
  cout << "---STUDENT DETAILS---" << endl;
  cout << "Students name is: Alex Michel" << endl;
  cout << "Students age is: 19 " << endl;
  cout << "Students score: 96" << endl;
  cout << "Students roll number: 50" << endl; 
}
};

int main() {
  Student s1; 
  s1.display();
return 0;
} 
```

### Output

```text
---STUDENT DETAILS---
Students name is: Alex Michel
Students age is: 19 3375104
Students score: 96
Students roll number: 50 
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program14.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program16.md">Next →</a>
    </td>
  </tr>
</table>
