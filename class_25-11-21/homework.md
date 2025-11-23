# Conditional if statement

## Roller Coaster

You’ll build this program in three small steps, using the class notes on conditional statements and Boolean logic (`notes.md`).

Theme: You’re helping an amusement park check if a rider can go on specific rides based on their height in centimeters. Valid human heights for this system are from 0 to 250 cm.

Starter code:

```cpp
#include <iostream>
using namespace std;

int main() {
    int height;
    cin >> height; // enter height in cm

    // Your code here

    return 0;
}
```

**Step 1** — Validate input (easy)
- If `height` is less than 0 or greater than 250, print: `Invalid` and stop.
- Otherwise, print: `Height Valid`.

**Step 2** — Add ride eligibility (add nested/else-if)
- Only when the height is valid, print which ride the person can take:
  - `Ride: Thrill Coaster` if `height >= 140`
  - `Ride: Junior Coaster` if `height >= 110`
  - `Ride: Kiddie Carousel` otherwise
- Keep the validation from Step 1 in place.

What to test
- Try inputs: `-10`, `300`, `95`, `110`, `139`, `140`, `200`.
- Check that only valid heights print `Height Valid` + a ride line, and invalid ones print `Invalid`.

## Triangle Type Checker

[Link to previous class last homework task](../class_25-11-14/homework.md#advanced--triangle-type-checker)

## Books and Boxes

Johnny is moving into a new home and needs to pack all his books into boxes. Each box can hold up to `box_capacity` books. Write a program that determines whether all books fit into the boxes and prints an appropriate message.

Check with:
- When `boxes = 2`, `books_count = 8`, `box_capacity = 5`, the program should print: `Books fit into boxes`.
- When `boxes = 3`, `books_count = 18`, `box_capacity = 5`, the program should print: `Books do not fit into boxes`.

Steps:
1. Variables `boxes`, `books_count`, `box_capacity` are read from console using `cin`.
2. Compute how many boxes are needed to pack all books.
3. Add a check to determine whether the books will fit into the available boxes and print the appropriate message.

```cpp
#include <iostream>
using namespace std;

int main() {
    int boxes;        // number of boxes
    int books_count;  // number of books
    int box_capacity; // capacity per box

    // Your code here

    return 0;
}
```


