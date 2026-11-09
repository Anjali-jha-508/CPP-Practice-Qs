# Program 15

Write a CPP program to create a class Product and implement a function outside the class to calculate the total price.

```cpp 
#include <iostream>
#include <string>
using namespace std;

class Product {
public:
    string name;
    int quantity;
    float price, discount, total_amount;

    void input();
    void total();
    void display();
}; 

void Product::input(){
    cout << "---PRPDUCT DETAILS---" << endl;
    cout << "Enter product name: ";
    getline(cin, name);
    cout << "Enter quantity: ";
    cin >> quantity;
    cout << "Enter price of one piece: ";
    cin >> price;
    cout << "Enter discount: ";
    cin >> discount;
}

void Product::total() {
    total_amount = (price * quantity) - discount;
}

void Product::display() {
    cout << endl << "---RECEIPT---" << endl;
    cout << "Product Name: " << name << endl;
    cout << "Quantity: " << quantity << endl;
    cout << "Price of 1 piece: " << price << endl;
    cout << "Discount: " << discount << endl;
    cout << "Total Amount: " << total_amount << endl; 
}

int main() {
    Product p1;
    p1.input();
    p1.total();
    p1.display();   
    return 0;
} 
```
---

### Output

```text
---PRODUCT DETAILS---
Enter product name: Wafers
Enter quantity: 7
Enter price of one piece: 15
Enter discount: 10

---RECEIPT---
Product Name: Wafers
Quantity: 7
Price of 1 piece: 15
Discount: 10
Total Amount: 95 
```
 
---
 
<table width="100%">
  <tr>
    <td align="left">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Function-%26-class/Program14.md">← Previous</a>
    </td>
    <td align="right">
      <a href="https://github.com/Anjali-jha-508/CPP-Practice-Qs/blob/main/Function-%26-class/Program16.md">Next →</a>
    </td>
  </tr>
</table> 
