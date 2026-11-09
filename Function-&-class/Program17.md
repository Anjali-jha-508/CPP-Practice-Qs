# Program 17

Write a CPP program to create a class Employee with data members name and salary. Define one function inside the class and another function outside the class to display the employee details.

```cpp 
#include <iostream>  
#include <string>
using namespace std;

class Employee {
public:
    string name, empID;
    int age, salary, bonus, total_salary;

    //functions inside the class
    void input() {
        cout << endl << "---ENTER DETAILS OF EMPLOYEE---" << endl;
        cout << "Enter name: ";
        getline(cin, name);
        cout << "Enter employee ID: ";
        getline(cin, empID);
        cout << "Enter age: ";
        cin >> age;
        cout << "Enter annual salary: ";
        cin >> salary;
        cout << "Enter bonus: ";
        cin >> bonus;
    } 
    void total() {
        total_salary = salary + bonus;
    }
    void display();
};

//function outside the class
void Employee::display() {
    cout << endl << "---DETAILS OF EMPLOYEE---" << endl;
    cout << "Name: " << name << endl;
    cout << "Employee ID: " << empID << endl;
    cout << "Age: " << age << endl;
    cout << "Annual Salary: " << salary << endl;
    cout << "Bonus: " << bonus << endl;
    cout << "Total Salary: " << total_salary << endl;
}

int main() {
    Employee e1;
    e1.input();
    e1.total();
    e1.display();   
return 0;
} 
```
---

### Output

```text
---ENTER DETAILS OF EMPLOYEE---
Enter name: Alex Michel
Enter employee ID: 23NJK0907
Enter age: 29
Enter annual salary: 900000
Enter bonus: 75000

---DETAILS OF EMPLOYEE---
Name: Alex Michel
Employee ID: 23NJK0907
Age: 29
Annual Salary: 900000
Bonus: 75000
Total Salary: 975000 
```  
---
 
<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Function-%26-class/Program16.md">← Previous</a>
    </td> 
  </tr>
</table> 
