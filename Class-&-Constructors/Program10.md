# Program 10
Write a CPP program to create a class Car with a default constructor that sets model = 101 and displays it.

```cpp
#include <iostream> 
using namespace std;

class Car {
public:
int model; 

Car() {
    model = 101; 
} 

void display() {
  cout << "model of the car is " <<  model;   
}
};

int main() {
    Car c1;
    c1.display();
    return 0;
} 
```
 
<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Program9.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Program11.md">Next →</a>
    </td>
  </tr>
</table>
