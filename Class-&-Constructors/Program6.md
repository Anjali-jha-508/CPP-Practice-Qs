# Program 6
Write a CPP program to create a class Rectangle with a default constructor that sets length = 5 and width = 4. Display the area.

```cpp
#include <iostream> 
using namespace std;

class Rectangle{
public:
int lenght, width, area;

Rectangle() {
    lenght = 5;
    width = 4;
    area = lenght * width;
}
void display() {
    cout << "Area of the rectangle, whose lenght is " << lenght << " and width is " << width << " is: " << area << endl;
} 
};

int main() {
    Rectangle r1;
    r1.display();
    return 0;
} 
```
 
<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Program5.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Program7.md">Next →</a>
    </td>
  </tr>
</table>
