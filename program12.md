# Program 12

Write a CPP program to create a class Product with product ID, name, quantity, and price. Calculate and display the total price.

```cpp
#include <iostream> 
#include <string>
using namespace std;

class Product {  
public: 
  string name;
  int ID; 
  float price, quantity, total;

void input() {
    cout << "Enter product name: ";
    getline(cin, name);
    cout << "Enter product ID: ";
    cin >> ID;
    cout << "Enter Quantity: ";
    cin >> quantity;
    cout << "Enter price of product: ";
    cin >> price; 
}    

void calcTotal() {
  total = price * quantity;
}

void display() {
  cout << "Product ID: " << ID << endl;  
  cout << "Product name: " << name << endl; 
  cout << "Quantity: " << quantity << endl;  
  cout << "Price: " << price << endl;
  cout << "Total Price: " << total << endl;
}
};

int main() {     
  Product p1;
  p1.input();
  p1.calcTotal();
  cout << endl << "---BILL---" << endl;
  p1.display();
return 0;
}
```

### Output

```text 
Enter product name: (example: ice cream, press enter)
Enter product ID: (example: 90, press enter)
Enter Quantity: (example: 2, press enter)
Enter price of product: (example: 10, press enter)
(after pressing enter)

---BILL---
Product ID: 90
Product name: ice cream
Quantity: 2
Price: 10
Total Price: 20
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program11.md">← Back</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class/program13.md">Next →</a>
    </td>
  </tr>
</table>
