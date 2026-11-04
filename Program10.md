# Program 10

Write a CPP program to create a class Number with a function inside the class to check whether a number is prime.

```cpp 
#include <iostream>  
using namespace std;

class Number {
public:
  int num, isPrime;
  
  void input() {
    cout << "Enter a number to check whether it's prime or not: ";
    cin >> num; 
  }
  void prime() {
     if (num <= 1) {
        isPrime = 0;
    } 
    else {
        // a prime number is only divisible by 1 and itself 
        // Check if n is divisible by any number from 2 to n-1
        for (int i = 2; i < num; i++) {
            if (num % i == 0) {
                isPrime = 0; // Found a factor, so it is not prime
            }
        }
    } 
    // Output the result
    if (isPrime == 0) {
        cout << num << " is not a prime number." << endl;
    } 
    else {
        cout << num << " is a prime number." << endl;
    }   
  } 
};

int main() {
  Number n1;
  n1.input();
  n1.prime();
return 0;
} 
```
---

### Output

```text
Enter a number to check whether it's prime or not: 9
9 is not a prime number. 
```
---

> **Explaining the code:**
> After taking the input number, first if condition checks if the number is negative or 0, due to which it can never be a Prime number also the else statement using for loop will check whether the number entered is divisible by anyother number except itself and 1. If any such number is encountered then again the isPrime factor becomes zero. After this for the final output there are two conditions, here the first if condition will tell the number is not prime because the isPrime event is turned to be zero, and now the remainig other event tells that the number is prime.


<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program9.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-questions./blob/functions-%26-class/Program11.md">Next →</a>
    </td>
  </tr>
</table>
