### Declaration and Initialization:
```
using System;
using System.Collections.Generic;

class Program
{
    static void Main()
    {
        // Declaration and initialization of a Stack of integers
        Stack<int> numberStack = new Stack<int>();

        // Push elements onto the stack (add to the top of the stack)
        numberStack.Push(1);
        numberStack.Push(2);
        numberStack.Push(3);
    }
}
```
### Push and Pop Operations:
```
// Push (add to the top of the stack)
numberStack.Push(4);

// Pop (remove from the top of the stack)
int poppedItem = numberStack.Pop();
```
### Peeking at the Top Element:
```
// Peek at the top element without removing it
int topItem = numberStack.Peek();
```
### Checking if the Stack Contains an Element:
```
bool containsTwo = numberStack.Contains(2);
```
### Iterating Through a Stack:
```
foreach (int number in numberStack)
{
    Console.WriteLine(number);
}
```
### Clearing the Stack:
```
numberStack.Clear();
```
Stacks are commonly used in scenarios where elements are processed in the reverse order they are added. Examples include managing function calls in a program (call stack), undo mechanisms in applications, or parsing expressions in reverse polish notation (postfix notation). The `Stack<T>` class provides efficient methods for adding, removing, and inspecting elements at the top of the stack.