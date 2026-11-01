# Program 5

Write a CPP program to create a class Circle with functions inside the class to calculate area and circumference.

```cpp 
#include <iostream> 
using namespace std;

class Circle {
  const double pi = 3.14159; 
public: 
  double area, radius, circumference;

void userinput() {
    cout << "Enter radius of the circle: ";
    cin >> radius;
}    

void calcArea() {
  area = pi * radius * radius;
} 

void calcCircum(){
  circumference = 2 * pi * radius;
}

void display() {
  cout << "The area of the circle with the radius " << radius << " is: " << area << endl; 
  cout << "The circumference of the circle with the radius " << radius << " is: " << circumference << endl;
}
};

int main() {
  Circle c1;
  c1.userinput();
  c1.calcArea();
  c1.calcCircum(); 
  c1.display();
return 0;
} 
```
---

### Output

```text
Enter radius of the circle:      (example 2, press enter)
(after pressing enter)
The area of the circle with the radius 2 is 12.5664
The circumference of the circle with the radius 2 is 12.5664 
```
---

> We came across this code earlier too, during class and object.


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program4.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program6.md">Next →</a>
    </td>
  </tr>
</table>


