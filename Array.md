## Array

**Array-** It is a collection of elements of the same type stored in contiguous memory locations.

### Declaring and Initializing Arrays:

```
// Integer array
int[] numbers = new int[5]; // Creates an array of integers with length 5

// String array
string[] names = new string[] { "John", "Jane", "Alice" };

// Integer array
int[] number = { 1, 2, 3, 4, 5 };
```

### Accessing Elements:

>Array elements are accessed using an index, starting from 0:
```
int firstNumber = numbers[0]; // Accesses the first element (index 0)
int secondNumber = numbers[1]; // Accesses the second element (index 1)
```
### Modifying Elements:
```
numbers[2] = 10; // Modifies the third element (index 2) to be 10
```
### Array Length:

>You can get the length of an array using the `Length` property:
```
int arrayLength = numbers.Length; // Returns the length of the array
```
### Iterating Through an Array:

```
foreach (int number in numbers)
{
    Console.WriteLine(number);
}
```

### Multidimensional Arrays:

>C# supports multidimensional arrays. For example, a 2D array:
```
int[,] matrix = new int[3, 3];
```


