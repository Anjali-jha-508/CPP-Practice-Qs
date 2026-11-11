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
