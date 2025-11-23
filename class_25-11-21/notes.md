
# Conditional statements and Boolean logic

Nesting if statements: https://www.w3schools.com/cpp/cpp_conditions_nested.asp  
Logical operators AND OR NOT: https://www.w3schools.com/cpp/cpp_conditions_logical.asp

# Class notes

**Nesting if statements** basic examples:
```cpp
#include <iostream>
using namespace std;

int main() {
    int score; 
    cin >> score; // 0..100
    
    if (score < 0) {
        cout << "Invalid" << endl;
    } else if (score > 100) {
        cout << "Invalid" << endl;
    } else {
        cout << "Grade Valid" << endl;
        
        // Here we know that score is valid, lets assign the grade
        if (score >= 90) cout << "Grade A";
        else if (score >= 40) cout << "Grade B";
        else cout << "Grade C";
    } 

    return 0;
}
```

We can make this better since first two conditions just ensure our input is valid.

```cpp
// If score is negative OR score is above 100, score is invalid.
if (score < 0 || score > 100) {
    cout << "Invalid" << endl;
} else {
    cout << "Grade Valid" << endl;
    
    if (score >= 90) cout << "Grade A";
    else if (score >= 40) cout << "Grade B";
    else cout << "Grade C";
}
```

Last we can make it as a named statement (variable).

```cpp
// Score is valid if it is in range [0; 100]
bool score_is_valid = score >= 0 && score <= 100;

// If score is valid, grade can be assigned.
if (score_is_valid) {
    cout << "Grade Valid" << endl;
    
    if (score >= 90) cout << "Grade A";
    else if (score >= 40) cout << "Grade B";
    else cout << "Grade C";
} else {
    cout << "Invalid" << endl;
}
```

## Logical operations

```cpp
int n = 60;

cout << (n < 200) << endl; // 1 == true == tiesa
cout << (n <= 0) << endl; // 0 == false == netiesa
```

```cpp
cout << "n is positive: " << (n > 0) << endl;

bool is_positive = n > 0;
cout << "is_positive: " << is_positive << endl;

if (is_positive) {
    // Do sth with n > 0
}
```

### AND && operation and OR || operation

```cpp
bool is_positive = n > 0;
bool is_even = n % 2 == 0;

cout << "n = " << n << endl;
cout << (n > 0) << " && " << (n % 2 == 0) << " = " << (n > 0 && n % 2 == 0) <<  endl;
cout << (n > 0) << " || " << (n % 2 == 0) << " = " << (n > 0 || n % 2 == 0) <<  endl;
```
