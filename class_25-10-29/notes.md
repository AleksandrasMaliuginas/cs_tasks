
# User input (2)

# Class notes

**Console input** & **Console output** & order of operations:
```cpp
#include <iostream>
using namespace std;

int main() {
    float distanceKm;  
    int stepMeters;    
    
    cout << distanceKm << endl;
    distanceKm = 2.5;
    cout << distanceKm << endl;
    
    cout << "Enter distance in Km: ";
    cin >> distanceKm;
    cout << distanceKm << endl;

    return 0;
}
```

Checking previous class homework:
```cpp
#include <iostream>
using namespace std;

int main() 
{
  float distanceKm;  
  int stepMeters;    
  
  int distanceMeters;
  int fullSteps;
  int leftoverMeters;
  
  cout << "Distance (km): ";
  cin >> distanceKm;
  
  cout << "Step (m): ";
  cin >> stepMeters;
  
  distanceMeters = distanceKm * 1000;
  fullSteps = distanceMeters / stepMeters;
  leftoverMeters = distanceMeters % stepMeters;
  
  cout << "Full steps: " << fullSteps << endl;
  cout << "Leftover (m): " << leftoverMeters << endl;

  return 0;
}
```
