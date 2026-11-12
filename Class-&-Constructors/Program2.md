# Program 2
Write a CPP program to create a class Number with a default constructor that sets num = 10 and displays it

```cpp
#include <iostream> 
using namespace std;

class Number{
public:
int num; //number variable is defined

Number() {
    num = 10; //it is set to 10 using default constructor
}
void display() {
    cout << "The number is: " << num << endl;
}
};

int main() {
  Number n1;  
  n1.display();
 return 0;
}  
```

<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Program1.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Program3.md">Next →</a>
    </td>
  </tr>
</table>
