# Program 7
Write a CPP program to create a class Circle with a default constructor that sets radius = 5 and displays it.

```cpp
#include <iostream> 
using namespace std;

class Circle{
public:
int radius;

Circle() {
    radius = 5;
}
void display() {
    cout << "Radius of the circle is " << radius; 
} 
};

int main() {
    Circle c1;
    c1.display();
    return 0;
} 
```
 
<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Program6.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Program8.md">Next →</a>
    </td>
  </tr>
</table>
