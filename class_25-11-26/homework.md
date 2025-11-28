# Reading and writing to a file

> 💡 Hint: To complete each task, follow the steps in the [class notes](./notes.md).

## Sum and product

File `data.txt` contains three integers.
Read them as `a`, `b`, `c` and write the results to `result.txt`:
  - Sum = `a + b + c`
  - Product = `a * b * c`

Example `data.txt`:
```txt
5 7 3
```

Expected output `result.txt`:
```txt
Sum: 15
Product: 105
```

## Discriminant of a quadratic

File `data.txt` contains three integers.
Read them as `a`, `b`, `c` (coefficients of a quadratic function), compute:
  - Discriminant `D = b*b - 4*a*c`
and write the discriminant to `result.txt`.

Example `data.txt`:
```txt
1 -3 2
```

Expected output `result.txt`:
```txt
Discriminant: 1
```

## Price calculation

File `data.txt` contains four values: `quantity` (int), `free_items` (int), `unit_price` (double), `tax_rate` (double).
Compute:
  - Billable quantity = `quantity - free_items`
  - Subtotal = `billable_quantity * unit_price`
  - Tax = `subtotal * tax_rate`
  - Total = `subtotal + tax`
Write all four results to `result.txt` (you may format money to 2 decimals).

Example `data.txt`:
```txt
10 2 3.50 0.21
```

Expected output `result.txt`:
```txt
Billable quantity: 8
Subtotal: 28.00
Tax: 5.88
Total: 33.88
```
