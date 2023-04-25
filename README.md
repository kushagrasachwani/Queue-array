# Queue-array
A queue is a linear data structure that follows the First-In-First-Out (FIFO) principle, which means the element that is inserted first is the one that comes out first. It is an ordered collection of elements where the insertion of new elements is done at one end (rear) and removal of existing elements is done from the other end (front).

Queues are widely used in various computer algorithms and systems, such as operating systems, web servers, and network routers. In programming, queues can be used to implement a variety of algorithms, such as Breadth-First Search (BFS) and job scheduling.

Some common operations that can be performed on a queue are:

1. Enqueue: adds an element to the rear of the queue
2. Dequeue: removes and returns the element from the front of the queue
3. Peek: returns the element at the front of the queue without removing it
4. Size: returns the number of elements in the queue
5. IsEmpty: checks if the queue is empty

Queues can be implemented using arrays, linked lists, or other data structures depending on the requirements and constraints of the system.
# Algoritm
Here is the algorithm for implementing a queue using an array:

Input: size of the queue, operations to be performed

Output: elements of the queue after performing operations

1. Create an array of size n to store the queue and initialize two variables "front" and "rear" to -1. These variables will keep track of the front and rear elements of the queue.
2. While performing the operations:
a .If the operation is "enqueue":
      i. Check if the queue is full by comparing "rear" with n-1. If it is full, print "Queue is full" and exit the operation.
      ii. Otherwise, increment "rear" by 1 and assign the value to the new element.
   b. If the operation is "dequeue":
      i. Check if the queue is empty by comparing "front" with "rear". If it is empty, print "Queue is empty" and exit the operation.
      ii. Otherwise, increment "front" by 1 to remove the element from the queue.
   c. If the operation is "display":
      i. Print all the elements of the queue from "front" to "rear".
3. After performing all the operations, print the final state of the queue.

Note: In step 2a, if the queue is implemented in a circular manner, we need to use the modulus operator to wrap around the rear pointer to the beginning of the array if it reaches the end.

This algorithm outlines the basic steps involved in implementing a queue using an array.
# Screenshot
![p7](https://user-images.githubusercontent.com/126184012/234296388-8f429f05-ea0a-49f0-8b3a-cb513f6b7b38.png)

