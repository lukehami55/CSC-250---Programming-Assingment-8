# Program Design
## Data Storage in Main
``` cpp
Scooter myScooter() //object
```
## Function Class Design
``` cpp
// Default constructor
Scooter::Scooter()

// Second constructor
Scooter::Scooter(string brand, float max_spd)

// Accessor functions
string Scooter::getType()
float Scooter::getMaxSpeed()
float Scooter::getCurrentSpeed()

// Mutator functions
void Scooter::setType(string brand)
void Scooter::setMaxSpeed(float max_spd)
void Scooter::setCurrentSpeed(float curr_spd)
void Scooter::speedUp()
void Scooter::slowDown()
```
## Time Estimates
|  | Estimated Time    | Actual Time    |
| :---:   | :---: | :---: |
| Program Design | 30   | 40   |
| Class Design |  30  | 45   |
| main | 10   | 10   |
| Program Test | 5   | 5   |
| Total Time | 75   | 100   |
