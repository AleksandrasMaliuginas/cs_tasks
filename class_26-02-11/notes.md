
# Skaitymas iš failo su `for`

Ciklas for: https://informatikosvbe.lt/programavimas-cpp/ciklai/for

# Pamokos užrašai

## Paprastas skaitymas iš failo

Nuskaitykime 2 skaičius iš failo:

```
# duomenys.txt
32
17.5
```

```cpp
ifstream failas("duomenys.txt");

int n;
double aukstis;

failas >> n;       // Iš failo nuskaityk skaičių     n[ 32 ]
failas >> aukstis; // Iš failo nuskaityk skaičių     aukstis[ 17.5 ]

failas.close();
```

## Kelių skaičių nuskaitymas naudojant `for`

Paprastas `for` ciklas, jei norime nuskaityti kelis skaičius (užrašyti `repeat(5) { ... }`):

```
# duomenys.txt
3
127.5
254
-73.2
```

```cpp
ifstream failas("duomenys.txt");

int n;
double skaicius;

failas >> n;       // Iš failo nuskaityk skaičių     n[ 32 ]

for (int i = 0; i < n; i++) {
    // Kitos dvi eilutės bus įvykdytos 3 kartus
    failas >> skaicius; // Iš failo nuskaityk skaičių     skaicius[ 17.5 ]
    cout << skaicius << endl; // Išvesti nuskaitytą skaičių į ekraną
}

failas.close();
```
