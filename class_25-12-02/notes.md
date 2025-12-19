
# Reading from file

Files: https://www.w3schools.com/cpp/cpp_files.asp

# Class notes

## Reading from file

Given a simple text file named `data.txt` with two numbers: the first is a price, and the second is a tax rate.

```txt
12 0.21
```

**First**, we read the data from a file and verify the values:
```cpp
#include <iostream> // input / output stream
#include <fstream> // file stream

using namespace std;

int main()
{
    ifstream input("data.txt"); // input file stream
    
    int price;
    double tax_rate;
    
    input >> price >> tax_rate;
    
    cout << "Price: " << price << endl;
    cout << "Tax rate: " << tax_rate << endl;

    input.close();
    return 0;
}
```
Expected output:
```txt
Price: 12
Tax rate: 0.21
```

**Second**, we add the calculation required to complete the task:
```cpp
// ...
    cout << "Price: " << price << endl;
    cout << "Tax rate: " << tax_rate << endl;
    
    double paid_in_taxes = price * tax_rate;
    cout << "Paid in taxes: " << paid_in_taxes << endl;
// ...
```
Expected output:
```txt
Price: 12
Tax rate: 0.21
Paid in taxes: 2.52
```

**Third**, once our program works as expected and we get the expected results, we write them to a results file:
```cpp
// ...
    double paid_in_taxes = price * tax_rate;
    cout << "Paid in taxes: " << paid_in_taxes << endl;

    ofstream out("result.txt"); // output file stream
    out << "Paid in taxes: " << paid_in_taxes << endl;

    out.close();
// ...
```
Expected output in `result.txt`:
```txt
Paid in taxes: 2.52
```