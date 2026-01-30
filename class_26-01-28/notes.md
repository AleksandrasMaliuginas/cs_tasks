
# Ciklai (`for` & `while`)

Ciklas while: https://informatikosvbe.lt/programavimas-cpp/ciklai/while  
Ciklas for: https://informatikosvbe.lt/programavimas-cpp/ciklai/for

# Pamokos užrašai

## `while` ciklas

Paprastas `while` ciklas, jei norime užrašyti `repeat(5)`:

```cpp
int n = 5;

int i = 0; // Pirma dalis
while (i < n) { // Salyga: 0 < 5  ->  1 < 5  ->  2 < 5  ...  5 < 5  NE
    cout << "Ciklas:   i = " << i << endl;
    
    i = i + 1; // Trečia dalis
}
```

## `for` ciklas

Paprastas `for` ciklas, jei norime užrašyti `repeat(5)`:

```cpp
int n = 5;

// for (Pirma dalis; Sąlyga; Trečia dalis)
for (int i = 0; i < n; i = i + 1) {
    cout << "Ciklas:     i = " << i << endl;
}
```

## Pavyzdys - Bėgikai

Duomenų faile nurodyta kiek bėgikų dalyvavo varžybose ir toliau surašyti visų bėgikų laikai sekundėmis. Užduotis atspausdinti visus bėgikų bėgimo laikus.

```cpp
ifstream failas("duomenys.txt");
int n;

failas >> n;

for (int i = 0; i < n; i = i + 1) {
    cout << "Bėgikas nr. " << i+1 << endl;
    
    int laikas;
    failas >> laikas;
    cout << laikas << " sec." << endl;
}

failas.close();
```
