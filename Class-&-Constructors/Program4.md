# Program 4
Write a CPP program to create a class Employee with a default constructor that sets salary = 5000 and displays it.

```cpp
#include <iostream> 
using namespace std;

class Employee{
public:
int salary; //number variable is defined

Employee() {
    salary = 5000; //it is set to 5000 using default constructor
}
void display() {
    cout << "Employee's salary is: " << salary << endl; //display the salary of employee
}
};

int main() {
  Employee e1;  
  e1.display();
 return 0;
} 
```
 
<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Program3.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Program5.md">Next →</a>
    </td>
  </tr>
</table>
