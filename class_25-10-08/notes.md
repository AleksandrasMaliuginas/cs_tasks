
# Variables

How to create (define) a variable: https://www.w3schools.com/cpp/cpp_variables.asp  
How to name a variable: https://www.w3schools.com/cpp/cpp_variables_identifiers.asp  
Some exapmles: https://www.w3schools.com/cpp/cpp_variables_reallife.asp  

# Class notes
```cpp
#include <iostream>
using namespace std;

int main() 
{
    cout << "Programos pradzia! \n"; // console out
    // cout << "Nenoriu kad sitas veiktu";
    
    // x y a b
    // pyrag_kiekis
    
    
    // To create (define) variable we use this:
    // type name = value;
    
    int x = 10; // int -> integer -> sveikas skaicius
    float f = 0.12;
    char c = 'R';
    string s = "word";
    
    int musu_kintamasis = 123 * 23 + 12 - 103 + 32; // creates a "box" with value inside
    // musu_kintamasis = 2770
    
    cout << musu_kintamasis << endl; // 2770
    
    cout << musu_kintamasis + 30 << endl; // 2800
    // musu_kintamasis = 2770
    
    cout << musu_kintamasis / 10 << endl; // 277
    
    cout << endl;
    
    
    musu_kintamasis = musu_kintamasis + 30;
    cout << musu_kintamasis << endl; // 2800
    cout << musu_kintamasis / 10 << endl; // 280
    
    return 0;
}
```
