# Readings: Stack and Queues

1. What's the difference between Stack and Queue?
- Difference between Stack and Queue
 

| Stack | Queue |
|---------|-----------|
|The stack is based on LIFO(Last In First Out) principle| The queue is based on FIFO(First In First Out) principle.|
|Insertion Operation is called Push Operation|	Insertion Operation is called Enqueue Operation|
|Deletion Operation is called Pop Operation| Deletion Operation is called Dequeue Operation|
|Push and Pop Operation takes place from one end of the stack|	Enqueue and Dequeue Operation takes place from a different end of the queue|
|The most accessible element is called Top and the least accessible is called the Bottom of the stack|The insertion end is called Rear End and the deletion end is called the Front End. |
|Simple Implementation |	Complex implementation in comparison to stack|
|Only one pointer is used for performing operations |	Two pointers are used to perform operations|
|Empty condition is checked using Top==-1| Empty condition is checked using 'Front==-1 OR Front==Rear+1' |
|Full condition is checked using Top==Max-1| Full condition is checked using Rear==Max-1|
|There are no variants available for stack| There are three types of variants i.e circular queue, double-ended queue and priority queue|
|Can be considered as a vertical collection visual| Can be considered as a horizontal collection  visual|
|Used to solve the recursive type problems| Used to solve the problem having sequential processing|

<br>
<br>

[resource](https://favtutor.com/blogs/stack-vs-queue)
<br>
<br>



2. What is Stacks and how to use it?
- A stack is a data structure comprised of a series of nodes with a reference pointing to the "next" node (no prev pointing reference).
- In the stack, we insert the element from one end with push operation and delete the element from the same end using pop operation. The end of the stack used to perform all the operations is called the top of the stack. Therefore, a stack follows the LIFO (Last In First Out) principle, which means the element that is inserted last will be the first element to come out of the stack.


            - FILO and LIFO: first item in will be the last item out
            - LIFO: last item in will be first item out


3. What is Queue?
- The queue is a linear data structure in which we can insert the element from one side of the list and delete the element from the other side of the list
