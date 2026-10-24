# Program 14

Write a CPP program to create a class Car with registration number, model, and price. Accept and display the car information. 

```cpp
#include <iostream> 
#include <string>
using namespace std;

class Car {  
public: 
  string model;
  int regNum, price;

void input() {
    cout << "Enter Model of the Car: ";
    getline(cin, model);
    cout << "Enter Registeration number of the Car: ";
    cin >> regNum;
    cout << "Enter price of the Car: ";
    cin >> price;
}    

void display() {
  cout << endl << "---CAR DETAILS---"<< endl;
  cout << "Model: " << model << endl;  
  cout << "Registeration Number: " << regNum << endl;   
  cout << "Price: " << price << endl;
}
};

int main() {     
  Car c1;
  c1.input(); 
  c1.display();
return 0;
}
```

### Output

```text 
Enter Model of the Car: MWS 89XKK
Enter Registeration number of the Car: 1234588
Enter price of the Car: 90999999

---CAR DETAILS---
Model: MWS 89XKK
Registeration Number: 1234588
Price: 90999999
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program12.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program15.md">Next →</a>
    </td>
  </tr>
</table>
