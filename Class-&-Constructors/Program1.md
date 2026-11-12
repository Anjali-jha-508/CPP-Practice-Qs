# Program 1

Write a CPP program to create a class Student with a default constructor that displays "Hello Student".

```cpp
#include <iostream>
#include <string>
using namespace std;

class Student{
public:
string name;
 
Student() {
     cout << "Enter students name: ";
  getline(cin, name);
  cout << "Hello " << name;
}
};

int main() {
  Student s1;  
 return 0;
} 
```

<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Overview.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Class-%26-Constructors/Program2.md">Next →</a>
    </td>
  </tr>
</table>
