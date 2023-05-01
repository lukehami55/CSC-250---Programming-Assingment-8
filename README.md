# Program Design
## Data Storage in Main
``` cpp
IntList myList; //object
```
Main creates an empty list, appends nodes, inserts nodes, and displays nodes.
## Function Class Design
``` cpp
// Default constructor
IntList()

// Second constructor
IntList(const IntList& obj)

// Accessor functions
string Scooter::getType()
float Scooter::getMaxSpeed()
float Scooter::getCurrentSpeed()

// Mutator functions
void appendNode(int);
void insertNode(int);
void deleteNode(int);
void displayList() const;
int countNodes() const
```
## Time Estimates
|  | Estimated Time    | Actual Time    |
| :---:   | :---: | :---: |
| Program Design | 30   | 40   |
| Class Design |  40  | 45   |
| main | 15   | 10   |
| Program Test | 5   | 5   |
| Total Time | 90   | 100   |
