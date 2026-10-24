# Program 2

Write a CPP program to create a class Student with data members name and age. Take input from the user and display the values.

```cpp
#include <iostream>
#include <string>
using namespace std;

class Student{
public:
  string name, surname;
  int age;
void userinput() {
    cout << "Enter students name: ";
    cin >> name >> surname;
    cout << "Enter students age: ";
    cin >> age;
}
void display() {
  cout << "Students name is: " << name << " " << surname << endl;
  cout << "Students age is: " << age << endl;
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
Enter students name:     (Enter any name in front of it for example Alex Michel and press enter)
Enter students age:      (Enter any age example 18)
Students name is: Alex  Michel  
Students age is: 18        (after pressing enter)
```

 

 

<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program1.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program3.md">Next →</a>
    </td>
  </tr>
</table>
