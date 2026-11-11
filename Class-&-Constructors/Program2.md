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
