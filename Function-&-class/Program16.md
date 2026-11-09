# Program 16

Write a CPP program to create a class Number with a function cube() defined outside the class to calculate the cube of a number.

```cpp 
#include <iostream>  
using namespace std;

class Number {
public:
  int num, cube;
 
    void input();
    void calcCb();
};    
  
  void Number::input() {
    cout << "Enter a number to calculate its square: ";
    cin >> num; 
  }

  void Number::calcCb() {
    cube = num * num * num;
    cout << "Cube of " << num << " is " << cube;      
  } 
 
int main() {
  Number n1;
  n1.input();
  n1.calcCb();
  return 0; 
} 
```
---

### Output

```text
Enter a number to calculate its square: 3
Cube of 3 is 27
```  
---
 
<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Function-%26-class/Program15.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Function-%26-class/Program17.md">Next →</a>
    </td>
  </tr>
</table> 
