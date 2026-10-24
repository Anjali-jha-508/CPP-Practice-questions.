# Program 9

Write a CPP program to create a class Student with three marks as data member num and a member function to check whether the number is even or odd.

```cpp
#include <iostream> 
using namespace std;

class Student {  
public: 
  int marks_sub1, marks_sub2, marks_sub3, Tmarks;

void input() {
    cout << "Enter marks of subject 1: ";
    cin >> marks_sub1;
    cout << "Enter marks of subject 2: ";
    cin >> marks_sub2;
    cout << "Enter marks of subject 3: ";
    cin >> marks_sub3;
}    
 
void calcTotal() {
  Tmarks = marks_sub1 + marks_sub2 + marks_sub3;
} 

void display() {
  cout << "Total marks is: " << Tmarks << endl; 
}
};

int main() {  
  Student s1;
  s1.input();
  s1.calcTotal();
  s1.display();
return 0;
}
```

### Output

```text 
Enter marks of subject 1:      (example 98, press enter)
Enter marks of subject 2:      (example 90, press enter)
Enter marks of subject 3:      (example 95, press enter)
(after pressing enter)
Total marks is: 283
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
