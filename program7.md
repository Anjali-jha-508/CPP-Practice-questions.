# Program 7

Write a CPP program to create a class Circle with data member radius and a member function to calculate the area of the circle.

```cpp
#include <iostream> 
using namespace std;

class Circle {
  const double pi = 3.14159; 
public: 
  double area, radius;

void userinput() {
    cout << "Enter radius of the circle: ";
    cin >> radius;
}    

void calcArea() {
  area = pi * radius * radius;
} 
 
void display() {
  cout << "The area of the circle with the radius " << radius << "is: " << area << endl; 
}
};

int main() {
  Circle c1;
  c1.userinput();
  c1.calcArea(); 
  c1.display();
return 0;
}
```

### Output

```text
Enter radius of the circle:      (example 2, press enter)
(after pressing enter)
The area of the circle with the radius 2 is 12.5664
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program6.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program8.md">Next →</a>
    </td>
  </tr>
</table>
