# Program 1

Write a CPP program to create a class Student with a data member name and display the student's name.

```cpp
#include <iostream>
#include <string>
using namespace std;

class Student{
public:
  string name;
void input() {
    cout << "Enter students name: ";
    cin >> name;
}
void display() {
  cout << "Students name is: " << name << endl;
}
};

int main() {
  Student s1;
  s1.input();
  s1.display();
return 0;
}
```

### Output

```text
Enter students name:     (Enter any name in front of it for example Alex and press enter)
Students name is: Alex   (after pressing enter)
```

<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/Overview.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program2.md">Next →</a>
    </td>
  </tr>
</table>
 
