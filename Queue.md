### Declaration and Initialization:
```
using System;
using System.Collections.Generic;

class Program
{
    static void Main()
    {
        // Declaration and initialization of a Queue of integers
        Queue<int> numberQueue = new Queue<int>();

        // Enqueue elements (add to the end of the queue)
        numberQueue.Enqueue(1);
        numberQueue.Enqueue(2);
        numberQueue.Enqueue(3);
    }
}
```
### Enqueue and Dequeue Operations:
```
// Enqueue (add to the end of the queue)
numberQueue.Enqueue(4);

// Dequeue (remove from the front of the queue)
int dequeuedItem = numberQueue.Dequeue();
```
### Peeking at the Front Element:
```
// Peek at the front element without removing it
int frontItem = numberQueue.Peek();
```
### Checking if the Queue Contains an Element:
```
bool containsTwo = numberQueue.Contains(2);
```
### Iterating Through a Queue:
```
foreach (int number in numberQueue)
{
    Console.WriteLine(number);
}
```
### Clearing the Queue:
```
numberQueue.Clear();
```
Queues are commonly used in scenarios where elements are processed in the order they are added, such as task scheduling, breadth-first searches, or handling requests in a network or message processing system. The `Queue<T>` provides efficient methods for adding, removing, and inspecting elements at the front and back of the queue.