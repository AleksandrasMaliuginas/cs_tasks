
# Variables (2) & User input

Data type | Variable types: https://www.w3schools.com/cpp/cpp_data_types.asp  
Data type examples: https://www.w3schools.com/cpp/cpp_data_types_reallife.asp

User Input `cin`: https://www.w3schools.com/cpp/cpp_user_input.asp  

# Class notes

**Console input** & variable types:
```cpp
#include <iostream>
using namespace std;

int main() 
{
  int a = 45;
  cout << a << endl;
  
  float age = 0;
  cin >> age; // console-INPUT
  
  cout << "Amzius " << age << endl;


  // Repeat the same if you want a "loop"
  age = 1;
  cin >> age; // console-INPUT
  
  cout << "Amzius " << age << endl;

  age = 2;
  cin >> age; // console-INPUT
  
  cout << "Amzius " << age << endl;
  
  
  // Or you can do it with the actual loop
  int kartai = 3;
  while (kartai > 0) {
    age = 2;
    cin >> age; // console-INPUT
    
    cout << "Amzius " << age << endl;
    
    kartai = kartai - 1;
  }
}
```

Checking previous class homework:
```cpp
#include <iostream>
using namespace std;

int main() 
{
  /**
   * Simple budget
   */  

  int pocketMoney = 100;
  int sandwichPrice = 4;
  int sandwiches = 6;
  
  int nereikalingas = 20; // nereikalingas = 20
  int asdf; // skaicius, kurio pavadinimas yra asdf. 

  int spent = sandwichPrice * sandwiches; // [spent] = 24
  int remaining = pocketMoney - spent; // box: remaining -> [pocketMoney] -> [spent] -> atimtis

  cout << "Spent: " << spent << " euros" << endl;
  cout << "Remaining: " << remaining << " euros" << endl;
    
  
  /**
   * Time conversion + variable types
   */ 
    
  int hours = -3; // 2.25
  cout << hours << endl;
  
  float svoris = 0.0003;
  cout << svoris << endl;
    
    return 0;
}
```
