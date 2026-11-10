# Program 1

Write a CPP program to create a class Student with a default constructor that displays "Hello Student".

```cpp
#include <iostream>
#include <string>
using namespace std;

class Student{
public:
string name;

void userinput() {
  cout << "Enter students name: ";
  getline(cin, name);
}
Student() {
  cout < "Hello " << name;
}
};

int main() {
  Student s1;
  s1.userinput();
  
```
