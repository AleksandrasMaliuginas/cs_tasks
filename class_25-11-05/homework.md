# While Loop Basics

## Count and Sum to N
Given the following code template:

```cpp
#include <iostream>
using namespace std;

int main() {
    int n;

    // TODO: read n using cin
    // TODO: using a while loop, print the numbers from 1 to n (inclusive), one per line
    // TODO: also compute the sum of 1..n and print it as: Sum: <value>

    return 0;
}
```

Your task:
- Read a positive integer `n`.
- Use a `while` loop to print the integers from 1 to `n`, one per line.
- After the sequence, print the total sum in the format `Sum: <value>`.

Example input:
```
5
```
Example output:
```
1
2
3
4
5
Sum: 15
```


## Multiplication Table (while)
Given the following code template:

```cpp
#include <iostream>
using namespace std;

int main() {
    int base;
    int limit;

    // TODO: read base and limit using cin
    // TODO: using a while loop, print lines from i = 1 up to i = limit
    //       in the format: base x i = <product>

    return 0;
}
```

Your task:
- Read two integers: `base` and `limit` (assume `limit >= 1`).
- Use a `while` loop to print exactly `limit` lines, for `i` from 1 to `limit`:
  - `base x i = <product>`

Example input:
```
6 4
```
Example output:
```
6 x 1 = 6
6 x 2 = 12
6 x 3 = 18
6 x 4 = 24
```
