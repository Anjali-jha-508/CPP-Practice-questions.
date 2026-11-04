# Program 13

Write a CPP program to create a class Rectangle and implement the area() function outside the class.

```cpp 
#include <iostream>
#include <string>
using namespace std;

class Rectangle {
public:
    float length, width, area;
    void input();
    void calcArea();
    void display();
};

    void Rectangle::input() {
        cout << "---ENTER DIMENSIONS OF RECTANGLE---" << endl;
        cout << "Enter length: ";
        cin >> length;
        cout << "Enter width: ";
        cin >> width;
    }
    void Rectangle::calcArea() { 
        area = length * width;
    }
    void Rectangle::display() {

        cout << "Area of the rectangle with lenght " << length << " and width " << width << " is " << area << endl;
    }

int main() {
    Rectangle r1;
    r1.input();
    r1.calcArea();
    r1.display();   
return 0;
}  
```
---

### Output

```text
---ENTER DIMENSIONS OF RECTANGLE---
Enter length: 4
Enter width: 5
Area of the rectangle with lenght 4 and width 5 is 20 
```
---
 
<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program12.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program14.md">Next →</a>
    </td>
  </tr>
</table> 
