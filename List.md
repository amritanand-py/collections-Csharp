
### Declaration and Initialization:

```
using System;
using System.Collections.Generic;

class Program
{
    static void Main()
    {
        // Declaration and initialization of a List of integers
        List<int> numbersList = new List<int>();

        // Adding elements to the List
        numbersList.Add(1);
        numbersList.Add(2);
        numbersList.Add(3);

        // Initializing a List with elements
        List<string> namesList = new List<string> { "John", "Jane", "Alice" };
    }
}
```
### Accessing and Modifying Elements:
```
// Accessing elements by index
int firstNumber = numbersList[0];

// Modifying elements by index
numbersList[1] = 10;
```
### Adding and Removing Elements:
```
// Adding elements
numbersList.Add(4);
numbersList.Insert(2, 5); // Inserting at a specific index

// Removing elements
numbersList.Remove(3);
numbersList.RemoveAt(0); // Removing by index
```
### Iterating Through a List:
```
// Iterating through elements using a foreach loop
foreach (int number in numbersList)
{
    Console.WriteLine(number);
}
```
```
for (int i = 0; i < numbersList.Count; i++)
{
    Console.WriteLine($"Element at index {i}: {numbersList[i]}");
}
```
### List Count:
```
int count = numbersList.Count; // Returns the number of elements in the List
```