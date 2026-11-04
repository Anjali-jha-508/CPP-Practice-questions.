# Program 7

Write a CPP program to create a class Marks with functions inside the class to calculate total, average and percentage.

```cpp 
#include <iostream>
#include <string>
using namespace std;

class Marks {
public:
  string name; 
  int rollNo, marks_sub1, marks_sub2, marks_sub3;
  float total, avg, perc; 

void userinput() {
   cout << "ENTER STUDENTS DETAILS" << endl;
   cout << "Name: ";
   getline(cin, name);
   cout << "Roll Number: ";
   cin >> rollNo;
   cout << "Marks in Subject 1 out of 100: ";
   cin >> marks_sub1;
   cout << "Marks in Subject 2 out of 100: ";
   cin >> marks_sub2;
   cout << "Marks in Subject 3 out of 100: ";
   cin >> marks_sub3;
}

void calcTotal() {
   total = marks_sub1 + marks_sub2 + marks_sub3;
}

void calcAvg() {
   avg = total / 3.0;
}

void calcPerc() {
   perc = (total / 300.0) * 100.0;
}

void display() {
   cout << endl << "---STUDENT DETAILS---" << endl;
   cout << "Name: " << name << endl;
   cout << "Roll Number: " << rollNo << endl;
   cout << "Total Marks: " << total << endl;
   cout << "Average Marks: " << avg << endl;
   cout << "Percentage: " << perc << "%" << endl;
}
};

int main() {
   Marks s1;
   s1.userinput();
   s1.calcTotal();
   s1.calcAvg();
   s1.calcPerc();
   s1.display();
return 0;
}   
```
---

### Output

```text
ENTER STUDENTS DETAILS
Name: Alex Josh
Roll Number: 9
Marks in Subject 1 out of 100: 90
Marks in Subject 2 out of 100: 98
Marks in Subject 3 out of 100: 97

---STUDENT DETAILS---
Name: Alex Josh
Roll Number: 9
Total Marks: 285
Average Marks: 95
Percentage: 95%
```
 

<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program6.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program8.md">Next →</a>
    </td>
  </tr>
</table>
