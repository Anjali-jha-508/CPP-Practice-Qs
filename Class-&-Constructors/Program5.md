# Program 5
Write a CPP program to create a class Addition with a default constructor that sets two numbers and displays their sum.

```cpp
#include <iostream> 
using namespace std;

class Addition{
public:
int num1, num2, sum; //number variable is defined

Addition(){
    num1 = 5;
    num2 = 10;
    sum = num1 + num2; // 2 numbers are given value and operated to addition
}
void display(){
    cout << "The sum of " << num1 << " and " << num2 << " is: " << sum << endl;
}
};

int main() {
    Addition add;
    add.display();
    return 0;
} 
```
