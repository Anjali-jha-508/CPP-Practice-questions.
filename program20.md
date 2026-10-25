# Program 20

Write a CPP program to define a class Time with hours, minutes, and seconds. Create an object to display the time. 

```cpp 
#include <iostream> 
using namespace std;

class Time {
public:
  int hours, minutes, seconds;
  
  void input() { 
    cout << "Enter time of birth in H::M::S pattern." << endl;
    cout << "Enter hours(H): ";
    cin >> hours;
    cout << "Enter minutes(m): ";
    cin >> minutes;
    cout << "Enter seconds(s): ";
    cin >> seconds;
  }  
 
  void display() {
    cout << endl << "Time of birth is: " << hours << "H::" << minutes << "M::" << seconds << "S" << endl;  
  }
};

int main() {
  Time t1;
  t1.input(); 
  t1.display(); 
return 0;
}
```

### Output

```text
Enter time of birth in H::M::S pattern.
Enter hours(H):      (example 11; press enter)
Enter minutes(m):    (example 59; press enter)
Enter seconds(s):    (example 40; press enter)

Time of birth is: 11H::59M::40
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program19.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program21.md">Next →</a>
    </td>
  </tr>
</table>

