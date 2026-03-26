# Namų darbas

## Išmokti mintinai

### `failas >> n;`

```cpp
ifstream failas("duomenys.txt");
int n;

failas >> n; // Ką daro šita eilutė?
```

Ką daro šita eilutė?  
Iš failo **nuskaito skaičių ir padeda jį į** kintamajį `n`;

### `for (int i = 0; i < n; i++) { ... }` == `repeat(5) { ... }`

```cpp
int n = 7;

for (int i = 0; i < n; i++) { // Ką daro šita eilutė?
    // Visas žemiau esantis codas bus pakartotas 7 kartus
    cout << "Kartas" << endl;
    // Visas auksčiau esantis codas bus pakartotas 7 kartus
}
```

Ką daro šita eilutė?  
Pakartoja žemiau esantį kodo blocką, **parašytą tarp riestinių skliaustų**, `n` kartų.

## 1 užduotis - Kuprinės pakavimas

Ruošiatės į žygį ir turite N daiktų, kuriuos norėtumėte pasiimti. Daiktų svoriai gramais yra nurodyti `duomenys.txt` faile.  
Parašykite programą, kuri:
1. Suskaičiuotų bendrą visų daiktų svorį gramais.
2. Pagal bendrą svorį nustatytų, kaip sunku bus nešti kuprinę:
   - Jei mažiau nei 2000 g — **lengva**
   - Jei nuo 2000 g iki 5000 g — **prasta**
   - Jei daugiau nei 5000 g — **sunku**

Įvestis (`duomenys.txt`):
```
5
800
1200
450
300
600
```

Rezultatas (išvestis, `cout`):
```
Bendras svoris: 3350 g
Kuprine nesti bus: iprasta
```

## 2 užduotis - Savaitės žingsniai

Telefone saugomi N dienų žingsnių skaičiai (kiekviena eilutė — vienos dienos žingsniai). Jie nurodyti `duomenys.txt` faile.  
Parašykite programą, kuri:

1. Suskaičiuotų bendrą žingsnių skaičių per visas dienas.
2. Pagal bendrą sumą nustatytų, kaip aktyvi buvo savaitė (ar laikotarpis):
   - Jei mažiau nei 35 000 žingsnių — **žema**
   - Jei nuo 35 000 iki 70 000 žingsnių — **vidutinė**
   - Jei daugiau nei 70 000 žingsnių — **aukšta**

Įvestis (`duomenys.txt`):
```
5
8000
1200
4500
300
600
```

Rezultatas (išvestis, `cout`):
```
Bendri zingsniai: 14600
Aktyvumas: zema
```
