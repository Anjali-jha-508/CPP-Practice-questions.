# Program 19

Write a CPP program to create a class Distance with distance in meters. Use an object to convert it into kilometers and meters. 

```cpp 
#include <iostream>
#include <string> 
using namespace std;

class Distance {
public:
  int m, km;
  
  void input() {
    cout << "Enter distance in meters(m): ";
    cin >> m;
  }  

  void mTOkm() {
    cout << endl << "1km = 1000m" << endl;
    km = m * 1000;
  }
 
  void display() {
    cout << endl << "----meters to kilometers---" << endl;
    cout << m << " meters = " << km << " kilometers" << endl; 
  }
};

int main() {
  Distance d1;
  d1.input();
  d1.mTOkm(); 
  d1.display(); 
return 0;
}
```

### Output

```text
Enter distance in meters(m): 20

1km = 1000m

----meters to kilometers---
20 meters = 20000 kilometers
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program18.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program20.md">Next →</a>
    </td>
  </tr>
</table>
