# Program 11
Write a CPP program to create a class Student with a default constructor that initializes student details and displays them.

```cppp
#include <iostream> 
#include <string>
using namespace std;

class Student{
public:
string name;
int age, rollno, marks;

Student() {
    name = "John Doe";
    age = 20;
    rollno = 12;
    marks = 85;
}
 
void display() {
    cout << "STUDENT DEATAILS" << endl;
    cout << "Name: " << name << endl;   
    cout << "Age: " << age << endl;
    cout << "Roll No: " << rollno << endl;
    cout << "Marks: " << marks << endl;
} 
};

int main() {
    Student s1;
    s1.display();
    return 0;
}
```
