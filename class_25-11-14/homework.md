# Conditional if statement

## Simple — Even or Odd
Given the following code template:

```cpp
#include <iostream>
using namespace std;

int main() {
    int n;

    // TODO: read n using cin
    // TODO: if n is even print "Even", otherwise print "Odd"

    return 0;
}
```

Your task:
- Read an integer `n`.
- If `n` is even, print `Even`, otherwise print `Odd`.

Example input:
```
7
```
Example output:
```
Odd
```

> Hint: To check if a number is odd, divide it by 2 and check the remainder. You can compute the remainder with the `%` operator.


## Intermediate — Grade Categorizer
Given the following code template:

```cpp
#include <iostream>
using namespace std;

int main() {
    int score; // 0..100

    // TODO: read score using cin
    // TODO: print a grade using if/else-if/else:
    //   90..100 -> "Grade: A"
    //   40..89  -> "Grade: B"
    //   0..39   -> "Grade: C"
    // You may assume the input is in 0..100.
    // BONUS: repeat reading and grading scores in a loop until a value < 0 or > 100 is entered; then stop (do not grade the terminating value).

    return 0;
}
```

Your task:
- Read an integer `score` in the range 0..100.
- Using if/else-if/else, print the corresponding grade exactly as specified.

Example input:
```
82
```
Example output:
```
Grade: B
```

> 🚀 Bonus: Make the program run in a loop: keep reading and grading scores until the user enters a number less than 0 or greater than 100. Then stop without grading that terminating value.


## Advanced — Triangle Type Checker

This task requires logical operators that were not covered in class. See: https://www.w3schools.com/cpp/cpp_conditions_logical.asp, to learn more.

Given the following code template:

```cpp
#include <iostream>
using namespace std;

int main() {
    int a, b, c;

    // TODO: read a, b, c using cin
    // TODO: first validate if a, b, c can form a triangle:
    //       (a + b > c) && (a + c > b) && (b + c > a)
    //       If not valid, print "Not a triangle"
    //       Otherwise:
    //         - if all sides equal -> "Equilateral"
    //         - else if two sides equal -> "Isosceles"
    //         - else -> "Scalene"

    return 0;
}
```

Your task:
- Read three integers `a`, `b`, `c` (side lengths).
- If they do not satisfy the triangle inequality, print `Not a triangle`.
- Otherwise classify and print exactly one of: `Equilateral`, `Isosceles`, `Scalene`.

Example input:
```
3 4 5
```
Example output:
```
Scalene
```

> 🚀 Bonus: Additionally detect right triangles and print `Right triangle` if the triangle is valid and satisfies the Pythagorean theorem.
