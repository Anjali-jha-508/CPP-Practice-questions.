# Program 2

Write a CPP program to create a class Rectangle with a member function inside the class to calculate its area and perimeter. 

```cpp 
#include <iostream>
#include <string>
using namespace std;

class Rectangle{
public:
   int length, breadth, area, perimeter;
void userinput() {
     cout << "---ENTER DIMENSIONS OF RECTANGLE---" << endl;
     cout << "Enter length: ";
     cin >> length;
     cout << "Enter breadth: ";
     cin >> breadth;
}

void calcArea() {
     area = length * breadth;      
}

void calcPerimeter() {
     perimeter = 2 * (length + breadth);
}

void display() {
      cout << endl << "---RECTANGLE DETAILS---" << endl;
      cout << "Length: " << length << endl;
      cout << "Breadth: " << breadth << endl;
      cout << "Area of rectangle: " << area << endl;
      cout << "Perimeter of rectangle: " << perimeter << endl;
}
};

int main() {
   Rectangle r1;
   r1.userinput();
   r1.calcArea();
   r1.calcPerimeter();
   r1.display();

return 0;
}   
```
---

### Output

```text
 ---ENTER DIMENSIONS OF RECTANGLE---
Enter length: 4
Enter breadth: 5

---RECTANGLE DETAILS---
Length: 4
Breadth: 5
Area of rectangle: 20
Perimeter of rectangle: 18 
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program1.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program3.md">Next →</a>
    </td>
  </tr>
</table>

