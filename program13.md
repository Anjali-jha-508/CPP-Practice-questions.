# Program 13

Write a CPP program to create class Temperature with a temperature value. Write a program to convert Celsius to Fahrenheit. 

```cpp
#include <iostream> 
using namespace std;

class Temperature {  
public: 
  float tempC, tempF;

void input() {
    cout << "Enter temperature in degree Celcius: ";
    cin >> tempC;
}    

void calcFar() {
  tempF = ((9.0/5.0) * tempC) + 32.0 ;
}

void display() {
  cout << endl << "---degree C to degree F conversion---"<< endl;
  cout << "Temperature in degree Celcius: " << tempC << endl;  
  cout << tempC << " degree Celcius =  " << tempF << " Fahrenheit." << endl;   
}
};

int main() {     
  Temperature t1;
  t1.input();
  t1.calcFar();
  t1.display();
return 0;
}
```

### Output

```text 
Enter temperature in degree Celcius: 10     (press enter)

---degree C to degree F conversion---
Temperature in degree Celcius: 10
10 degree Celcius =  50 Fahrenheit.
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program12.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program14.md">Next →</a>
    </td>
  </tr>
</table>
