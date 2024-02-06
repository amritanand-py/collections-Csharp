
### Declaration and Initialization:
```
using System;
using System.Collections.Generic;

class Program
{
    static void Main()
    {
        // Declaration and initialization of a Dictionary with keys of type string and values of type int
        Dictionary<string, int> ages = new Dictionary<string, int>();

        // Adding key-value pairs to the Dictionary
        ages["John"] = 25;
        ages["Jane"] = 30;
        ages["Alice"] = 22;
    }
}
```
### Accessing and Modifying Elements:
```
// Accessing elements by key
int johnsAge = ages["John"];

// Modifying elements by key
ages["Jane"] = 31;
```
### Checking for Key Existence:
```
// Checking if a key exists
bool containsJane = ages.ContainsKey("Jane");
```
### Iterating Through a Dictionary:
```
foreach (KeyValuePair<string, int> pair in ages)
{
    Console.WriteLine($"{pair.Key}: {pair.Value} years old");
}
```
### Removing Elements:
```
// Removing a key-value pair by key
ages.Remove("Alice");

// Clearing all key-value pairs from the Dictionary
ages.Clear();
```
Dictionaries are useful when you need to associate values with unique keys. They provide fast lookups based on keys, making them efficient for scenarios where quick retrieval of values based on some identifier is required.