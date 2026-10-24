# Program 16

Write a CPP program to create a class Rectangle with data members length and width. Calculate and display the area.

```cpp
#include <iostream> 
using namespace std;

class Rectangle{
public: 
  int length, width, area, perimeter;

void userinput() {
    cout << "Enter the length of the rectangle: ";
    cin >> length;
    cout << "Enter the width of the rectangle: ";
    cin >> width;
}

void calcArea() {
  area = length * width;
}

void calcPeri() {
  perimeter = 2 * (length + breadth);
}

void display() {
  cout << "The area of the rectangle is: " << area << endl; 
  cout << "The perimeter of the rectangle is:  " << perimeter << endl;
}
};

int main() {
  Rectangle r1;
  r1.userinput();
  r1.calcArea();
  r1.calcPeri();
  r1.display();
return 0;
}
```

### Output

```text
Enter the length of the rectangle:    (example 5)
Enter students age:      (example 4)
The area of the rectangle is: 20      (after pressing enter)
The perimeter of the rectangle is: 18
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program15.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program17.md">Next →</a>
    </td>
  </tr>
</table>
