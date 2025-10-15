# Using cin

## Basic Input and Arithmetic
Given the following code template:

```cpp
#include <iostream>
using namespace std;

int main() {
    int a;
    int b;

    // TODO: read a and b using cin
    // TODO: compute sum = a + b
    // TODO: print the inputs and the result exactly as shown below

    return 0;
}
```

Your task:
- Read two integers from input (store in `a` and `b`).
- Compute `sum = a + b`.
- Print exactly these three lines (with your input values and result).

Example input:
```
8 5
```
Example output:
```
Input a: 8
Input b: 5
Sum: 13
```


## Division and Remainder (mixed types)
Given the following code template:

```cpp
#include <iostream>
using namespace std;

int main() {
    float distanceKm;   // e.g., 2.5
    int stepMeters;     // e.g., 70

    // TODO:
    // 1) convert km to meters as an integer: distanceMeters = distanceKm * 1000
    // 2) compute fullSteps = distanceMeters / stepMeters
    // 3) compute leftoverMeters = distanceMeters % stepMeters
    // 4) print the inputs and the results exactly as shown below

    return 0;
}
```

Your task:
- Read a floating-point number `distanceKm` and an integer `stepMeters`.
- Convert kilometers to meters as an integer and use `/` and `%` to compute:
  - `fullSteps` (how many whole steps fit into the distance)
  - `leftoverMeters` (the remaining meters)
- Print exactly these four lines (with the values you used/computed).

Example input:
```
2.5 70
```
Example output:
```
Distance (km): 2.5
Step (m): 70
Full steps: 35
Leftover (m): 50
```


## Three Inputs (no loops) — Bonus: with a loop
Given the following code template:

```cpp
#include <iostream>
using namespace std;

int main() {
    float x1;
    float x2;
    float x3;

    // TODO (no loops):
    // 1) read x1, x2, x3 using cin
    // 2) compute sum = x1 + x2 + x3
    // 3) compute avg = sum / 3
    // 4) print exactly as shown below

    // BONUS: Implement using a loop (for or while) that reads 3 values.

    return 0;
}
```

Your task (no loops):
- Read three floating-point values `x1`, `x2`, `x3`.
- Compute their sum and average.
- Print exactly these four lines (with your inputs/results).

Example input:
```
3 4.5 2.5
```
Example output (format may vary slightly depending on float precision):
```
Values: 3, 4.5, 2.5
Sum: 10
Average: 3.33333
```

> 🚀 Bonus: Implement the program using a loop that reads 3 values and computes the same sum and average. Use either `for` or `while`.

> 💯🚀🎯 Extra bonus: Let the first input specify how many values to read; then read that many numbers and compute the sum and average.
