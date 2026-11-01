# Program 1

Write a CPP program to create a class Student with a function inside the class to display student details.

```cpp 
#include <iostream>
#include <string>
using namespace std;

class Student{
public:
  string name, surname, specialization;
  int age, div;
  float score;
void userinput() {
    cout << "----:ENTER STUDENTS DATA:---" << endl;
    cout << "Enter students name: ";
    cin >> name >> surname;
    cout << "Enter students age: ";
    cin >> age;
    cout << "Enter students division: ";
    cin >> div;
    cout << "Enter students score: ";
    cin >> score;
    cin.ignore();
    cout << "Enter students Specialization: ";
    getline(cin, specialization); 
}
void display() {
  cout << endl << "----:STUDENT DETAILS:----" << endl;
  cout << "Students name is: " << name << " " << surname << endl;
  cout << "Students age is: " << age << endl;
  cout << "Students division: " << div << endl;
  cout << "Students score: " << score << endl; 
  cout << "Students specialization: " << specialization << endl; 
}
};

int main() {
  Student s1;
  s1.userinput();
  s1.display();
return 0;
}
```

### Output

```text
 ----:ENTER STUDENTS DATA:---
Enter students name: Alex Michel
Enter students age: 18
Enter students division: 8
Enter students score: 97.63
Enter students Specialization: Cyber Security

----:STUDENT DETAILS:----
Students name is: Alex Michel
Students age is: 18
Students division: 8
Students score: 97.63
Students specialization: Cyber Security
```
---
This program might look similar to what we saw earlier, just some more details have been taken and displayed.
> `cin.ignore()`: this have been used after taking a float value input and before taking a string value input using get line, this helps to remove the extra garbage input.

> `getline(cin, specialization)`: using getline we can take more than one string as an input. 

----
<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Overview.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program2.md">Next →</a>
    </td>
  </tr>
</table>

