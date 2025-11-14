
# Conditional if statement

If: https://www.w3schools.com/cpp/cpp_conditions.asp  
Else: https://www.w3schools.com/cpp/cpp_conditions_else.asp
Else if: https://www.w3schools.com/cpp/cpp_conditions_elseif.asp  

# Class notes

**If statement** basic examples:
```cpp
#include <iostream>
using namespace std;

int main() {
    // just if
    int temperature = 25;
    if (temperature > 20) {
        cout << "It is warm outside." << endl;
    }

    // if and else
    bool isRaining = true;
    if (isRaining) {
        cout << "Take an umbrella." << endl;
    } else {
        cout << "No umbrella needed." << endl;
    }

    // if else if
    int score = 75;
    if (score >= 90) {
        cout << "Grade: A" << endl;
    } else if (score >= 60) {
        cout << "Grade: Pass" << endl;
    } else {
        cout << "Grade: Fail" << endl;
    }

    return 0;
}
```
