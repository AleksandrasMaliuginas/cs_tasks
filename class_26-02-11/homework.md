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



## 1 užduotis - Žaidimo lygiai

Žaidime žaidėjas pereina lygius rinkdamas taškus. Duomenų faile `duomenys.txt` pirmasis skaičius nurodo, kiek lygių buvo įveikta. Toliau pateikiami kiekvieno lygio taškai. Atspausdinkite tik tuos lygių taškus, kurie yra **1000 ar daugiau**.

Įvestis (`duomenys.txt`):
```
6
850
1200
999
1500
1000
400
```

Rezultatas (išvestis, `cout`):
```
1200
1500
1000
```

## 2 užduotis - Trumpų dainų grojaraštis

Draugas atsiuntė N dainų, iš kurių reikia sudaryti trumpų dainų drojaraštį. Trumpos dainos yra ne ilgesnės už 3 minutes.  
Dainų trukmė sekundėmis yra nurodyta `duomenys.txt` faile. Parašykite programą, kuri atspausdintų tik tas dainų trukmes, kurios bus įdėtos į grojaraštį.

Įvestis (`duomenys.txt`):
```
6
200
150
180
45
300
120
```

Rezultatas (išvestis, `cout`):
```
150
180
45
120
```
