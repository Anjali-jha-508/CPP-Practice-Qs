# Program 8
Write a CPP program to create a class Number with a default constructor that sets a number and checks whether it is even or odd.

```cpp
#include <iostream> 
using namespace std;

class Number{
public:
int num;

Number() {
    num = 5;
    if(num%2 == 0) {
      cout << num <<" is odd";
    } 
    else{
      cout << num <<" is even";
    }  
} 
};

int main() {
    Number n1;
    return 0;
} 
```
 
<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Program7.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Program9.md">Next →</a>
    </td>
  </tr>
</table>
