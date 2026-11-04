# Program 12

Write a CPP program to create a class Student and define the display() member function outside the class 
using the scope resolution operator ::.

```cpp 
#include <iostream>
#include <string>
using namespace std;

class Student {
    public:
    string name, Grade;
    int rollNo;
    float marks, score;
    
    void input();
    void Display();
};

void Student::input() {
    cout << "Enter Name: ";
    getline(cin, name);
    cout << "Enter Roll No: ";
    cin >> rollNo;
    cout << "Enter Grade: ";
    cin >> Grade;
    cout << "Enter Marks: ";
    cin >> marks;
    cout << "Enter Score: ";
    cin >> score;
}
 
void Student::Display() {
    cout << endl << "---STUDENT DETAILS---" << endl; 
    cout << "Name: " <<  name << endl;
    cout << "Roll No: " << rollNo << endl;
    cout << "Grade: " << Grade << endl;
    cout << "Marks: " << marks << endl;
    cout << "Score: " << score << "%" << endl;
}

int main() {
    Student s1;
    s1.input();
    s1.Display();
    return 0;
}   
```
---

### Output

```text
Enter Name: Alex Michel
Enter Roll No: 9
Enter Grade: A
Enter Marks: 495
Enter Score: 99 

---STUDENT DETAILS---
Name: Alex Michel
Roll No: 9
Grade: A
Marks: 495
Score: 99% 
```
> In this program, we have created the member functions within the class and then defined it further outside the class.
>
> This is done using the scope resolutions (::). 

---

 
<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program11.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program13.md">Next →</a>
    </td>
  </tr>
</table> 
