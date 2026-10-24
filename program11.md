# Program 11

Define a class Book with book ID, title, author, and price. Write a program to accept and display the details. 

```cpp
#include <iostream> 
#include <string>
using namespace std;

class Book {  
public: 
  string title, author;
  int ID, price;

void input() {
    cout << "Enter title of the book: ";
    getline(cin, title);
    cout << "Enter authors name: ";
    getline(cin, author);
    cout << "Enter ID number of the book: ";
    cin >> ID;
    cout << "Enter price of the book: ";
    cin >> price; 
}    
 
void display() {
  cout << "Title: " << title << endl;  
  cout << "Author: " << author << endl; 
  cout << "ID number: " << ID << endl;  
  cout << "Price: " << price << endl;
}
};

int main() {     
  Book b1;
  b1.input();
  cout << endl << "---BOOK DETAILS---" << endl;
  b1.display();
return 0;
}
```

### Output

```text 
Enter title of the book:      (example: Never ending summer, press enter)
Enter authors name:           (example: Coollen Hoover, press enter)
Enter ID number of the book:  (example: 89799, press enter)
Enter price of the book:      (example: 890, press enter)
(after pressing enter)
---BOOK DETAILS---
Title: Never ending summer
Author: Coollen Hoover
ID number: 89799
Price: 890
```


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program10.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/Class-%26-object/program12.md">Next →</a>
    </td>
  </tr>
</table>
