# Program 3 
Write a CPP program to create a class Student with a default constructor that sets age = 18 and displays it.

```cpp
#include <iostream> 
using namespace std;

class Student{
public:
int age; //number variable is defined

Student() {
    age = 18; //it is set to 18 using default constructor
}
void display() {
    cout << "Student's age is: " << age << endl; //display the age of student
}
};

int main() {
  Student s1;  
  s1.display();
 return 0;
} 
```
 
<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Program2.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Program4.md">Next →</a>
    </td>
  </tr>
</table>
