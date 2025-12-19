
# Reading from a file

Files: https://www.w3schools.com/cpp/cpp_files.asp

# Class notes

## Reading from a file

A basic program to read a number from a file and check whether it is divisible by 3.

```cpp
#include <iostream>
#include <fstream>

using namespace std;

int main()
{
    ifstream input_file("failas.txt"); // Open the existing file.
    int number = 87; // box [number = 87]
    // cout << number << endl;
    
    // cin >> number; // [number = 32]
    // cout << number << endl;
    
    input_file >> number; // [number = 303]
    cout << number << endl;
    
    // A number is divisible by 3 when the remainder is 0
    // number % 3 == 0
    // If number % 3 == 0, then it is divisible by 3
    cout << "Liekana: " << number % 3 << endl;
    
    // if (/* salyga */) {
    //     /* jei tiesa */
    // }
    int liekana = number % 3; // [liekana = 0]
    if (liekana == 0) { // jei liekana yra 0
        cout << "Dalus is 3" << endl;
    } else {
        cout << "Skaicius nedalus is 3." << endl;
    }
    
    input_file.close();

    return 0;
}
```