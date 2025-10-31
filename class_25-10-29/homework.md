# Using cin

## Ticket Counter: Total Tickets
Given the following code template:

```cpp
#include <iostream>
using namespace std;

int main() {
    // TODO: read the two inputs using cin
    // TODO: perform the necessary calculation based on the task
    // TODO: print the inputs and the final result

    // BONUS: also compute and print the total price (adult: 12 euros, child: 8 euros)

    return 0;
}
```

Your task:
- Read two integers representing the number of adults and children.
- Based on these inputs, compute the total number of tickets.
- Print the inputs and the total in a clear format.

> 🚀 Bonus: Given adult ticket price is 12 euros and child ticket price is 8 euros, compute and print the total price.


## Juice Bottling (mixed types)
Given the following code template:

```cpp
#include <iostream>
using namespace std;

int main() {
    float juiceLiters;  // e.g., 2.5
    int bottleMl;       // e.g., 70

    // TODO:
    // 1) convert liters to milliliters as an integer: totalMl = juiceLiters * 1000
    // 2) compute fullBottles = totalMl / bottleMl
    // 3) compute leftoverMl = totalMl % bottleMl
    // 4) print the inputs and the results exactly as shown below

    return 0;
}
```

Your task:
- Read a floating-point number `juiceLiters` and an integer `bottleMl`.
- Convert liters to milliliters and use `/` and `%` to compute:
  - `fullBottles` (how many whole bottles you can fill)
  - `leftoverMl` (remaining milliliters)
- Print exactly these four lines (with the values you used/computed).

Example input:
```
2.5 70
```
Example output:
```
Juice (L): 2.5
Bottle (ml): 70
Full bottles: 35
Leftover (ml): 50
```


## Exam Scores (no loops) — Bonus: with a loop
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
- Read three floating-point exam scores `x1`, `x2`, `x3`.
- Compute their total and average.
- Print exactly these four lines (with your inputs/results).

Example input:
```
3 4.5 2.5
```
Example output (format may vary slightly depending on float precision):
```
Scores: 3, 4.5, 2.5
Total: 10
Average: 3.33333
```

> 🚀 Bonus: Implement the program using a loop that reads 3 values and computes the same total and average. Use either `for` or `while`.

> 💯🚀🎯 Extra bonus: Let the first input specify how many scores to read; then read that many numbers and compute the total and average.
