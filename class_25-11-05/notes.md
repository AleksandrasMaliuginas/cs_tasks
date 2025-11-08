
# While loop

While loop basics: https://www.w3schools.com/cpp/cpp_while_loop.asp  
Examples: https://www.w3schools.com/cpp/cpp_while_loop_reallife.asp  


# Class notes

**While loop** example:
```cpp
#include <iostream>
using namespace std;

int main() {
    int n = 3;
    // cin >> n;
    
    float x;
    float sum = 0;
    
    while (n > 0) {
        // cout << "n = " << n << " Iveskit skaiciu: " << endl;
        cout << "Iveskit skaiciu: " ;
        
        cin >> x; // x = 3
        sum = sum + x; // sum = 3 + 3 = 6
        
        n = n-1;
    }
    
    cout << "Suma: " << sum;

    // 1. if 3 > 0
    // Labas
    // n = 3-1 = 2
    // 2. if 2 > 0
    // Labas
    // n = 2-1 = 1
    // 3. if 1 > 0
    // Labas
    // n = 1-1 = 0
    // 4. if 0 > 0 -> EXIT loop

    return 0;
}
```
